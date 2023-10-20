# Starter Next/Hardhat Project

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/


# MyToken Smart Contract

## Description

This Solidity smart contract implements a standard ERC20 token with additional functionalities like minting and burning tokens. It utilizes the OpenZeppelin library for secure and audited token functionality.

## License

This smart contract is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Prerequisites

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

## Installation

1. Clone the repository or create a new Solidity file and paste the code.
2. Make sure you have the OpenZeppelin library installed:
