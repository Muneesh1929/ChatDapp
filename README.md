# ChatDapp - Decentralized Chat Application

🚀 A full-stack **decentralized chat application** built with **Next.js, Hardhat, and Ethereum smart contracts**.  
This project allows users to connect via wallet, send/receive messages, and experience secure Web3 communication.

## 🔧 Tech Stack
- **Frontend:** Next.js, React, Context API
- **Blockchain:** Solidity, Hardhat
- **Styling:** CSS, Custom Components
- **Backend:** Smart contracts deployed on Ethereum testnet

## 📂 Project Structure
- `/contracts` → Solidity smart contracts
- `/pages` → Next.js frontend pages
- `/Components` → Reusable UI components
- `/Context` → State management
- `/Utils` → Helper functions
- `/scripts` → Deployment scripts
- `/test` → Smart contract test cases

## 🚀 How to Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ChatDapp.git
   cd ChatDapp-main
````

2. Install dependencies:

   ```bash
   npm install
   ```
3. Start Hardhat node:

   ```bash
   npx hardhat node
   ```
4. Deploy contracts:

   ```bash
   npx hardhat run scripts/deploy.js --network localhost
   ```
5. Run frontend:

   ```bash
   npm run dev
   ```

## 📸 Features

* 🔗 Wallet Connect (MetaMask)
* 💬 Send & Receive messages on blockchain
* 🛡️ Decentralized & Secure
* 🌐 Next.js frontend with smooth UI
