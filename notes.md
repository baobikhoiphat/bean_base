// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "forge-std/Test.sol";
import "../src/YourContract.sol";

contract YourContractTest is Test {
    YourContract public contractInstance;

    function setUp() public {
        // Create fork or deploy locally
        contractInstance = new YourContract();
    }

    function testExample() public {
        contractInstance.doSomething();
        assertEq(contractInstance.getValue(), 1);
    }
}


Contracts Deployed: 10+
Contracts Deployed: 10+
