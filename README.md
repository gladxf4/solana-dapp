# Solana Wallet Connection dApp

## Overview

This decentralized application (dApp) allows users to connect their Phantom Wallet, view their Solana (SOL) balance, and send SOL to other wallet addresses. Built with Next.js and TypeScript, this dApp leverages the Solana blockchain for fast and low-cost transactions.

## Features

- **Connect Phantom Wallet**: Users can easily connect their Phantom wallet to the dApp.
- **View SOL Balance**: After connecting, users can view their current SOL balance.
- **Send SOL**: Users can send SOL to any Solana wallet address.

## Technologies Used

- **Next.js**: A React framework for server-rendered applications.
- **TypeScript**: A superset of JavaScript that adds static typing.
- **Solana Web3.js**: A JavaScript library for interacting with the Solana blockchain.
- **Phantom Wallet**: A popular wallet for managing Solana tokens and interacting with dApps.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- Phantom Wallet installed in your browser.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/gladxf4/solana-dapp.git
   cd solana-dapp
   ```

2. Install the required dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```

4. Open your browser and navigate to `http://localhost:3000` to view the dApp.


### How To Use:

1. Click on the "Connect Wallet" button to connect your Phantom Wallet.
2. Once connected, your wallet address and current SOL balance will be displayed.
3. Enter the recipient's wallet address and the amount of SOL you want to send.
4. Click the "Send SOL" button to initiate the transaction.
