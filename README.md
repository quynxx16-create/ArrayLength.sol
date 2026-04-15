# ArrayLength.sol
ArrayLength.sol
pragma solidity ^0.8.20;
contract ArrayLength {
    uint[] public arr;

    function add(uint x) public {
        arr.push(x);
    }

    function getLength() public view returns(uint) {
        return arr.length;
    }
}
