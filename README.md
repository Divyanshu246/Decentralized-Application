# 🧾 Ethereum File Metadata DApp (index2.html)

This is a simple **decentralized application (DApp)** frontend built in plain HTML/JavaScript (`index2.html`). It allows users to upload **file metadata** (like filename, hash, and description) to the **Ethereum blockchain** using a smart contract and Web3.js.

## 📁 File

- `index2.html`: The main DApp interface (connects to MetaMask, reads input fields, and interacts with the smart contract).

## ⚙️ Features

- Connects to MetaMask wallet
- Uploads file metadata (not the actual file) to the blockchain
- Uses Web3.js to interact with Ethereum smart contract
- Displays transaction confirmation and stored data

## 🔧 Prerequisites

- MetaMask installed and connected
- A deployed smart contract (on local Ethereum network or testnet like Goerli)
- A local HTTP server (to serve `index2.html`)
- Web3.js library included (via CDN or locally)

## 🚀 How to Run

1. Make sure your smart contract is deployed (e.g., via Remix or Hardhat)
2. Update the smart contract address and ABI in `index2.html`
3. Serve `index2.html` using a local web server:

### Use VS Code Live Server
- Install the **Live Server** extension in VS Code
- Right-click `index2.html` → **"Open with Live Server"**

