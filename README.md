# 🏞️ Land Registration DApp for Ethereum

A decentralized application (DApp) for secure, transparent, and efficient land registration built on the Ethereum blockchain using smart contracts, IPFS, and zero-knowledge proofs.


## 🚀 Project Overview

This DApp enables users to:

- 🧑‍🌾 Register as landowners
- 🌍 Register land details securely
- 🔍 Search for land by unique ID
- 💰 Set properties for sale and define pricing
- 🤝 Buy/sell land via peer-to-peer interaction
- 🔐 Use zero-knowledge proofs (ZKPs) for validation
- ☁️ Upload and store property documents using IPFS

The backend is powered by **Solidity smart contracts**, deployed using **Truffle**, and the frontend is built in **React.js** with **Tailwind CSS**. MetaMask handles wallet interactions.



## 🛠 Tech Stack

| Layer            | Technology                            |
|------------------|----------------------------------------|
| **Blockchain**   | Ethereum (Ganache), Solidity           |
| **Framework**    | Truffle                                |
| **Frontend**     | React.js, Tailwind CSS                 |
| **Wallet**       | MetaMask                               |
| **Storage**      | IPFS (via Web3.Storage or Pinata)      |
| **Backend API**  | Node.js, Express                       |
| **Privacy Layer**| Circom, Zero-Knowledge Proofs (ZKPs)   |


## 📁 Project Structure

Land-Registration-DApp/
├── backend/
│ ├── contracts/ # Smart Contracts (LandRegistry, Verifier)
│ ├── migrations/ # Truffle migration scripts
│ ├── scripts/ # Utility/test scripts
│ ├── src/ # Express backend code
│ └── zk/ # ZKP circuits and proofs
├── frontend/
│ ├── public/ # Static files
│ └── src/ # React components, pages, services
└── README.md


## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/RufinaM03/Land-Registration-DApp-for-Ethereum.git
cd Land-Registration-DApp-for-Ethereum
2. Install Dependencies
Backend

bash
Copy
Edit
cd backend
npm install
Frontend

bash
Copy
Edit
cd ../frontend
npm install
3. Start Local Blockchain (Ganache)
Open Ganache GUI or CLI on port 7545 (or update web3Config.js if needed)

4. Compile & Deploy Smart Contracts
bash
Copy
Edit
cd ../backend
truffle compile
truffle migrate --network development
5. Start Backend Server
bash
Copy
Edit
node src/index.js
6. Start Frontend
bash
Copy
Edit
cd ../frontend
npm start
Then open http://localhost:3000 in your browser.

## Project Information

✨ Account Fetch via MetaMask
📋 User Registration
🔐 Unique Identity Commitment Generation (for ZKP)
🏠 Home Page
📑 Property Registration
📁 Upload Document to IPFS
🔎 Transaction Details & ZKP Backend View
💸 Ownership Transfer & Sale Process (John Doe)


🛡️ Security
Smart contracts thoroughly tested
Wallet-based authentication using MetaMask
Transaction privacy via zk-SNARKs (ZKPs)

🤝 Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss your ideas.






