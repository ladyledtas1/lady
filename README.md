// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract TheGraphPin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract DunePin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
