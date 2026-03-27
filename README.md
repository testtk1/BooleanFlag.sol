# BooleanFlag.sol
Deploy a contract on Base

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BooleanFlag {
    bool public flag;

    function setFlag(bool _flag) public {
        flag = _flag;
    }
}

