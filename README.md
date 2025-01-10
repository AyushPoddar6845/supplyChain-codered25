# Building and Deploying a Blockchain Supply Chain Management DApp

Building and Deploying a Blockchain Supply Chain Management DApp

Blockchain Supply chain management plays a critical role in ensuring efficient operations and maintaining consumer trust. This project focuses on developing and deploying a decentralized application (DApp) powered by blockchain technology to streamline supply chain management processes.

Our DApp utilizes the inherent transparency and immutability of blockchain to provide a secure and transparent platform for tracking goods at every stage of the supply chain. Leveraging smart contracts, the DApp automates various tasks such as verifying product authenticity, recording transactions, and managing inventory in real-time.

## Features

- **Decentralized Tracking:** Provides a secure and transparent platform for tracking shipments across the supply chain.
- **Smart Contract Automation:** Automates tasks such as shipment creation, status updates, and payment handling using Ethereum smart contracts.
- **Transparent Records:** Ensures immutable and transparent records of all transactions, reducing fraud and enhancing trust.
- **Real-Time Updates:** Tracks and updates shipment status in real-time for all users.
- **User Authentication:** Enables secure and seamless wallet-based authentication via MetaMask.

## Technologies Used

- **Next.js:** Framework for creating the user interface and managing server-side rendering.
- **Ethereum:** Blockchain network for deploying smart contracts and enabling decentralized interactions.
- **MetaMask:** Wallet integration for user authentication and Ethereum transactions.
- **Ganache:** Local blockchain environment for development and testing.
- **TailwindCSS:** CSS framework for designing a responsive and elegant user interface.
- **Solidity:** Programming language used to write smart contracts for the supply chain logic.
- **Hardhat:** Development environment for testing, deploying, and managing Ethereum-based smart contracts.

## Project Overview

![alt text](https://raw.githubusercontent.com/AyushPoddar6845/supplyChain-codered25/refs/heads/main/Images/Screenshot%202025-01-10%20074411.png)

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MetaMask](https://metamask.io/) browser extension
- [Ganache](https://trufflesuite.com/ganache/) for local blockchain deployment
- [Hardhat](https://hardhat.org/) development framework

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-github-username/blockchain-supplychain-dapp.git
   cd blockchain-supplychain-dapp

   ```

2. Create a .env file in the root of the project and add the required environment variables.

   ```bash
   NEXT_PUBLIC_CONTRACT_ADDRESS=your_deployed_contract_address
   NEXT_PUBLIC_INFURA_API_KEY=your_infura_api_key

   ```

3. Install the required dependencies:

   ```bash
   npm install

   ```

4. Start Ganache and configure the network in MetaMask to connect to the local blockchain.

5. Compile and deploy the smart contracts using Hardhat:

   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network ganache

   ```

6. Start the development server:

   ```bash
   npm run dev

   ```

7. Open your browser and navigate to http://localhost:3000 to access the DApp.

## Usage

- Connect Wallet: Connect your MetaMask wallet to the application.
- Create Shipment: Enter shipment details to create a new shipment on the blockchain.
- Track Shipment: View the status of shipments in real-time.
- Update Status: Change the shipment status as it moves through the supply chain.
- Complete Shipment: Finalize shipments and process payments securely.
