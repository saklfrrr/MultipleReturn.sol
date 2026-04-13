# MultipleReturn.sol
MultipleReturn.sol
pragma solidity ^0.8.20;
contract MultipleReturn {
    function get() public pure returns(uint, bool) {
        return (1, true);
    }
}
