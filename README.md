# Solana Wallet Manager

## Overview

Solana Wallet Manager is a Node.js CLI application designed for seamless management of Solana wallets. This tool empowers users to perform key wallet operations, including creating new wallets on the Solana blockchain, transferring funds between wallets, and securely managing up to 500 wallets.

## Features

- **Create New Wallets:** Generate new Solana wallets effortlessly, ensuring a quick and secure onboarding process.

- **Transfer Funds:** Facilitate the easy transfer of funds between Solana wallets, streamlining financial transactions on the blockchain.

- **Secure Management:** Store and manage up to 500 wallets securely, providing a comprehensive solution for users dealing with multiple wallets.

- **Intuitive CLI Interface:** Enjoy a user-friendly command-line interface that makes interactions with the application straightforward and accessible.

- **Advanced Operations:** Perform additional operations such as checking wallet balances, viewing transaction history, and updating wallet details.

## Dependencies

- Node.js 
- inquirer
- discord-webhook-node 
- clear-console 
- node-fetch 
- fs 
- path 
- @solana/web3.js 
- bs58 
- axios 
- os 

## Installation

To install the required dependencies, make sure you have Node.js installed on your machine, then run the following command in your terminal:

npm install

## Wallet Management

### A) Creating and Adding Wallets

To add an existing wallet, select "Manage Solana Wallets" from the main menu, then choose "Add Existing Wallet." Next, enter a name (any name) and the private key of the wallet. Your wallet will then be added.

To create a new wallet, select "Manage Solana Wallets" -> "Create a new Wallet" from the main menu. Then, enter the wallet's name and the number of wallets you want to create. Each subsequent wallet (if you want to create more than one) will be named: enteredname2, enteredname3, enteredname4, and so on. The first added wallet will be the default main wallet (can be changed, see below).

### B) Viewing/Deleting/Changing Names

To view your wallets and their balances, select "Manage Solana Wallets" -> "View my wallets" -> "View wallets balances" from the main menu. You will see all your wallets and their balances.

To rename a wallet: "Manage Solana Wallets" -> "View my wallets" -> "Rename a wallet"

To delete: "Manage Solana Wallets" -> "View my wallets" -> "Delete a wallet"

To change the main wallet: "Manage Solana Wallets" -> "View my wallets" -> "Set main wallet"

### 3. Distribution

To distribute Solana from the main wallet to all others, select: "Distribute Solana." Next, specify the amount of Solana and confirm the operation.

### 4. Collecting Solana to Main Wallet

To collect Solana from all wallets to the main one, select: "Collect all solana to main wallet."

All added wallets (name, private, and public keys) are stored in the wallets.json file.

If you specify a webhook, you will receive messages after collecting Solana, distributing, and creating new wallets.


