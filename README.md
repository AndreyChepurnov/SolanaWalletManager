# Solana Wallet Manager

## Overview

Solana Wallet Manager is a Node.js CLI application designed for seamless management of Solana wallets. This tool empowers users to perform key wallet operations, including creating new wallets on the Solana blockchain, transferring funds between wallets, and securely managing up to 500 wallets.

## Features

- **Create New Wallets**: Generate new Solana wallets effortlessly, ensuring a quick and secure onboarding process.
- **Transfer Funds**: Facilitate the easy transfer of funds between Solana wallets, streamlining financial transactions on the blockchain.
- **Secure Management**: Store and manage up to 500 wallets securely, providing a comprehensive solution for users dealing with multiple wallets.
- **Intuitive CLI Interface**: Enjoy a user-friendly command-line interface that makes interactions with the application straightforward and accessible.
- **Advanced Operations**: Perform additional operations such as checking wallet balances, viewing transaction history, and updating wallet details.

## Installation 

To install the required dependencies, make sure you have Node.js installed on your machine, then run the following command in your terminal:

### npm install

To run the app open the BabloTool.bat file. Enjoy!

## Usage

1. **Creating and Adding Wallets**: 
   - To add an existing wallet, select "Manage Solana Wallets" from the main menu, then choose "Add Existing Wallet." Next, enter a name and the private key of the wallet.
   - To create a new wallet, select "Manage Solana Wallets" -> "Create a new Wallet" from the main menu. Enter the wallet's name and the number of wallets you want to create.

2. **Viewing/Deleting/Changing Names**:
   - To view your wallets and their balances, select "Manage Solana Wallets" -> "View my wallets" -> "View wallets balances" from the main menu.
   - To perform other actions like renaming or deleting a wallet, follow the corresponding options in the menu.

3. **Distribution and Collection**:
   - To distribute Solana from the main wallet to all others, select "Distribute Solana." Specify the amount of Solana and confirm the operation.
   - To collect Solana from all wallets to the main one, select "Collect all solana to main wallet."

All added wallets (name, private, and public keys) are stored in the wallets.json file.



