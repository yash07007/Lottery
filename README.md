# Lottery Contract

A simple lottry contract which allows people to take part in a lottery by submitting minimum amount of contribution and then picks random winner and transfers the accumlated amount to it.

# Code Information

`./Contracts` directory contains Lottry contract.

`./test` directory contains mocha driven tests for the contracts.

`./complie.js` is responsible to complile `Contacts/Lottery.sol` with help of `solc` library and return ABI and Bytecode for contract.

`./deploy.js` is responsible to deploy the contract on ethereum node with help of infura API.
