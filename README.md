# SimpleMessageList.sol
Contract deployed via Web3 SimpleMessageList.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleMessageList {
    string[] public msgs;

    function add(string memory _m) public {
        msgs.push(_m);
    }
}
