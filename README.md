# Blockchain-based-Marketplace

A decentralized marketplace application built on the Ethereum blockchain. This project allows users to buy and sell items using Ethereum, leveraging smart contracts to handle transactions securely and transparently.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Acknowledgements](#acknowledgements)

## Installation

Follow the steps below :

### Prerequisites

Ensure you have the following software installed:

- [Node.js](https://nodejs.org/en/download/)
- [Truffle](https://www.trufflesuite.com/truffle)
- [Ganache](https://www.trufflesuite.com/ganache)
- [MetaMask](https://metamask.io/)

### Clone the Repository
```bash
git clone https://github.com/Mohanshi04/Blockchain-based-Marketplace.git
```
```bash
cd marketplace
```

### Install Dependencies
```bash
npm install
```

### Configure the Blockchain
- Open Ganache and start a new workspace.
- Note the RPC server URL (usually http://127.0.0.1:7545).
- Update truffle-config.js to match Ganache settings.

### Deploy Smart Contracts
```bash
truffle migrate --reset
```

### Start the Application
```bash
npm start
```

## Usage
To use this project, follow these steps:

- Open the application in your browser (usually at http://localhost:3000).
- Connect MetaMask to your local blockchain provided by Ganache.
- Create an account or log in using MetaMask.
- Use the interface to list items for sale or purchase items.

## Features
Decentralized Marketplace: Buy and sell items using Ethereum.
Smart Contracts: Secure and transparent transactions.
MetaMask Integration: Easy wallet management and transaction signing.
Accessibility : Accessible on various devices.

## Acknowledgements
Truffle
Ganache
MetaMask
