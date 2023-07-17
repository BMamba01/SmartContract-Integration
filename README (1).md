
# SmartContract-Integration

This project includes the integration of our smart contract with the front end using react and node js.


## Description

In this contract, the functionality of the basic crypto wallet is implemented. Where users can `Deposit` and `WithDraw` the `ETH Tokens`. Also, users can check their balance by connecting their `Metamask` wallet with the app. User can also check their Transaction history and which account they are currently using for those transactions.
## Pre-Requisites

1. You need to have the knowledge of HTML , React js and Node js.
2. You should have knowledge of solidity.
## How to run?


To run this project you have to follow specific steps:-
  - Inside the project directory, type `npm i` in the terminal.
  - Open the second terminal, and enter `npx hardhat node`.  (This will initiate hardhat)
  - Open the third terminal and type, `npx hardhat run --network localhost scripts/deploy.js`. (This will deploy the contract)
   - After installing the necessary dependencies, type `npm run dev` to start the server.
## Tech used

For Front-End part: `ReactJS`, `NodeJS`.
For Contract: `Solidity`