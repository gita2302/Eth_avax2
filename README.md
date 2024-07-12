
# Digital Decentralized Banking Service

This React application demonstrates a simple decentralized banking service using Ethereum and MetaMask. It allows users to connect their MetaMask wallet, view their account balance, and perform deposit and withdrawal operations.

## Description

This program is a React-based frontend for interacting with an Ethereum smart contract. It utilizes the ethers.js library to communicate with the Ethereum blockchain and MetaMask for wallet integration. The application provides a user interface for connecting a MetaMask wallet, displaying the account balance, and performing deposit and withdrawal transactions.

## Getting Started

### Dependencies

- React
- ethers.js
- MetaMask browser extension

### Executing program

1. Ensure you have Node.js and npm installed on your system.
2. Install the required dependencies:
   ```
   npm install react ethers
   ```
3. Make sure you have the MetaMask browser extension installed and set up.
4. Replace the `contractAddress` in the code with your deployed smart contract address.
5. Run the React application:
   ```
   npm start
   ```

## Usage

1. Open the application in your web browser.
2. If MetaMask is not installed, you'll see a message prompting you to install it.
3. Click the "Connect your Metamask wallet Please" button to connect your MetaMask wallet.
4. Once connected, you'll see your account address and balance.
5. Use the "Deposit 50 ETH" and "Withdraw 16 ETH" buttons to perform transactions.

## Code Overview

The main components of the code are:

- State management using React hooks (`useState`, `useEffect`)
- MetaMask wallet connection and account management
- Interaction with the Ethereum smart contract using ethers.js
- User interface for displaying account information and transaction buttons

Key functions:
- `getWallet()`: Initializes the connection to MetaMask
- `connectAccount()`: Connects the user's MetaMask account
- `getATMContract()`: Creates an instance of the smart contract
- `getBalance()`: Retrieves the account balance from the smart contract
- `deposit()`: Performs a deposit transaction
- `withdraw()`: Performs a withdrawal transaction

## Authors
Gitanjali
gitanjali.e16525@cumail.in

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

