## Hello World Contract
This Solidity program is a simple "Hello World" program that demonstrates the basic syntax and functionality of the Solidity programming language. The purpose of this program is to serve as a starting point for those who are new to Solidity and want to get a feel for how it works.

# Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a single function that returns the string "Hello World!". This program serves as a simple and straightforward introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.

## Getting Started

## Installing
To use this contract, you will need to have the following installed:

Node.js (version 14 or higher) npm (version 6 or higher) Truffle Suite (version 5 or higher) You can install Truffle Suite using npm by running the following command: npm install -g truffle

## Executing Program
To execute the Solidity smart contract code you provided for the token "EverCoin," you will need to follow these steps:
Compile the Contract:
Open a Solidity development environment like Remix IDE or use a Solidity compiler to compile the contract code.
Ensure that the code compiles without any errors before proceeding to deployment.
Deploy the Contract:
Deploy the compiled contract to an Ethereum network or a local blockchain for testing and execution.
Use tools like Remix IDE, Truffle, or a web3 provider like MetaMask to deploy the contract.
Interact with the Contract:
Once the contract is deployed, you can interact with it by calling the mint and burn functions.
Use a web3 provider like MetaMask to interact with the deployed contract and execute the minting and burning operations.
Testing:
Test the functionality of the contract by minting tokens to addresses and burning tokens from addresses.
Verify that the contract behaves as expected and that the balance checks in the burn function work correctly.
Transaction Confirmation:
Confirm and sign transactions when interacting with the contract through your web3 provider to execute the mint and burn operations.

## Running the Program
To run the program, follow these steps:

In the Truffle console, create a new instance of the contract:

let contract = await HelloWorld.deployed() Call the mint function to create new tokens

contract.mint("0x1234567890abcdef", 100) contract.mint("0x1234567890abcdef", 100)

Call the burn function to destroy tokens: contract.burn("0x1234567890abcdef", 50)

Check the balance of an address: contract.balances("0x1234567890abcdef")

## Help
If you encounter an error while compiling the contract, make sure that you have the correct version of Solidity installed. If you encounter an error while deploying the contract, make sure that you have a local Ethereum network set up and running.

## Authors
Rovie Rei Mangila METACRAFTERS

## License
This project is licensed under the Rovie Rei Mangila License - MIT License

Copyright (c) 2023 MetacrafterChris

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
