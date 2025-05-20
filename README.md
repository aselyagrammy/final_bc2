# 💡 Trusted Crowdfunding Platform Using a Smart Contract

## 📌 Overview

Traditional crowdfunding platforms often suffer from a lack of **transparency**, **accountability**, and **investor trust**. According to recent reports:

* **85%** of startups delay delivery,
* **14%** never deliver what was promised to investors.

This project addresses those issues by leveraging **blockchain technology** to create a **trusted crowdfunding platform** where:

* Investors can **track fund usage**,
* **Smart contracts** ensure funds are **locked** and only **released on milestone progress**,
* Fraud and misuse are drastically reduced.

## 🛠️ Features

* ✅ **Smart Contract-Based Escrow System**
  Funds are held securely using smart contracts and only released when project milestones are achieved.

* 🔍 **Transparent Fund Flow**
  Investors can see exactly how their funds are being used and by whom.

* 🔐 **Decentralized Trust**
  Eliminates the need for a centralized third party — trust is managed on-chain.

* 🌐 **MetaMask Integration**
  Investors interact with the platform securely through their MetaMask wallets.

## ⚙️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript
* **Blockchain**: Solidity (Smart Contracts), Ethereum Testnet
* **Wallet**: MetaMask
* **Backend**: Node.js, Express.js
* **Development Tools**: Hardhat / Truffle, Web3.js or Ethers.js

## 🧪 How It Works

1. A project creator submits a campaign with detailed milestones.
2. Investors fund the project via MetaMask.
3. Funds are locked in a smart contract.
4. Project creators must request milestone approvals to unlock the next portion of funds.
5. Funds are released automatically if milestones are verified.

## 🧰 Tools Used

* [MetaMask](https://metamask.io/)
* [Node.js](https://nodejs.org/)
* [Solidity](https://soliditylang.org/)
* [Hardhat](https://hardhat.org/) / [Truffle](https://trufflesuite.com/)
* [Ethereum Testnet](https://chainlist.org/)
* [Web3.js](https://web3js.readthedocs.io/) or [Ethers.js](https://docs.ethers.org/)

## 🚀 Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/trusted-crowdfunding.git
   cd trusted-crowdfunding
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Connect MetaMask to the appropriate testnet (e.g., Goerli, Holesky).

4. Compile and deploy the smart contract

   ```bash
   npx hardhat compile
   npx hardhat run scripts/deploy.js --network goerli
   ```

5. Start the backend server

   ```bash
   node server.js
   ```

6. Open the frontend in your browser and connect your MetaMask wallet.

## 👥 Team & Contribution

This project was developed as part of a university blockchain course assignment. Contributions are welcome!

## 📄 License

MIT License

