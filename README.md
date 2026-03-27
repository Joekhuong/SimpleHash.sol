# SimpleHash.sol
Remix - Deploy Contract On Base Network SimpleHash.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleHash {
    function hash(string memory _text) public pure returns (bytes32) {
        return keccak256(abi.encodePacked(_text));
    }
}
