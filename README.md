# Pet adoption smart contract

### Goal: Configure Solidity development environment on Vscode & Directory Structure

<br/>

> A Dapp which associates an Ethereum addresss with a pet to be adopted.

> Write the smart contract and front-end logic for its usage

- The store has space for 16 pets at a given time

- The store already has a database of pets

<br/>

- ### Directory Structure

contracts/ : Contains the Solidity source files for our smart contracts. There is an important contract in here called Migrations.sol, which we will discuss later.

migrations/ : Truffle uses a migration system to handle smart contract deployments. A migration is an additional special smart contract that keeps track of changes.

test/ : Contains both JS and Soliditty test for our smart contracts.

truffle-config.js : Truffle configuration file

- ### Compiling and Migrating

1. Compilation

We need to compile Solidity code to bytecode for EVM to execute, as if translating human-readable Solidity to machine language.

> 1. truffle compile

- ### Ganache

A personal blockchain for Ethereum development you can use to deploy contracts, develop applications, and run tests.
