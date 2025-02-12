# MetroChain

MetroChain is a blockchain-based real estate tokenization platform built using Solidity, Hardhat, and deployed on the Ethereum Sepolia testnet. This project allows users to tokenize real estate assets as NFTs using the ERC-721 standard.

## 🚀 Features
- **Real Estate Tokenization**: Convert real estate assets into NFTs.
- **Ethereum Smart Contracts**: Built using Solidity.
- **Deployment on Sepolia**: Smart contracts deployed on the Ethereum Sepolia testnet.
- **Etherscan Verification**: Verified contract on Etherscan for transparency.

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```sh
$ git clone https://github.com/your-repo/MetroChain.git
$ cd MetroChain
```

### 2️⃣ Install Dependencies
```sh
$ yarn install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file and add the following:
```sh
ALCHEMY_API_KEY=your_alchemy_api_key
PRIVATE_KEY=your_wallet_private_key
ETHERSCAN_API_KEY=your_etherscan_api_key
```

---

## ⚡ Deploying the Smart Contract

### 1️⃣ Compile Contracts
```sh
$ yarn hardhat compile
```

### 2️⃣ Deploy to Local Blockchain
```sh
$ yarn hardhat run scripts/deploy.js --network localhost
```

### 3️⃣ Deploy to Sepolia Testnet
```sh
$ yarn hardhat run scripts/deploy.js --network sepolia
```

---

## 🔎 Verify Contract on Etherscan
```sh
$ yarn hardhat verify --network sepolia <DEPLOYED_CONTRACT_ADDRESS>
```

---

## 🔍 View on Etherscan
Once deployed, check your contract on **[Sepolia Etherscan](https://sepolia.etherscan.io/)** by entering the contract address.

---

## 📜 License
This project is licensed under the MIT License.

---

## 💡 Future Improvements
- Add a frontend for real estate asset management.
- Implement a marketplace for trading property NFTs.
- Integrate with IPFS for decentralized property metadata storage.

---

### 💬 Need Help?
If you encounter any issues, feel free to open an issue in the repository or reach out!

