# Web3 Coding Exercise 1

## Overview
The process for this interview is to showcase your familiarity with a small subset of tools commonly used by
the SE team to showcase features of a SKALE Chain or in the process of helping partners integrate.

## How this works?
The process is straight-forward. You should follow the steps below to create the final outcome as requested.

## Exercise
1. Setup a [Hardhat](https://hardhat.org) project locally on your computer in either JavaScript or Typescript
2. Remove all the scripts, contracts, and tests from the project.
3. Create a smart contract called HelloWorld in [solidity](https://docs.soliditylang.org/en/v0.8.17) 
4. Your smart contract should have one function helloWorld that returns a string "Hello World"
5. You should create a deployment script to deploy your contract
6. Your script should also call and print the helloWorld function to the console

## Bonus #1
1. Create a new smart contract called "Manager"
2. Initialize the contract with the address of the Hello World contract as a private variable called helloAddress
3. Add a public function called "doStuff" which should call the "helloWorld" on the Hello World contract and return the return value of that function
4. Modify the script created in step #6 under the initial Exercise steps above to deploy the Manager contract or Create a new deployment script for the Manager contract.
5. Call the "doStuff" function and print the result to the console

## Bonus #2
1. Add a test file for HelloWorld contract [Mocha](https://mochajs.org), [Chai](https://www.chaijs.com)
2. Add a `describe` block for helloWorld() function
3. Add an `it` block that checks the return value of the helloWorld() function against `Hello World`

