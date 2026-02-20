# contract44.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Web3 wallet interaction mock contract
contract Contract44 {
    address public lastCaller;

    function callMe() public {
        lastCaller = msg.sender;
    }
}
