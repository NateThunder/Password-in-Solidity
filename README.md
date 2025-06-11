🔐 Password-in-Solidity
This is my first basic Solidity project where I experiment with storing and verifying passwords on the Ethereum blockchain. The project starts with a basic plaintext password implementation and evolves into a more secure version using hashing techniques.

📚 Overview
Smart contracts are public by nature, so storing passwords on-chain requires careful consideration. This project demonstrates:

✅ A simple contract with a hardcoded plaintext password.

🔐 A secure version using keccak256 hashing to verify a password without storing it in plain text.

🛠️ Tech Stack
Solidity – Smart contract language

Remix IDE – For testing and deploying contracts

MetaMask – Optional, for interacting with the contracts

📂 Project Structure
bash
Copy
Edit
Password-in-Solidity/
│
├── contracts/
│   ├── SimplePassword.sol          # Basic contract with plaintext password
│   └── HashedPassword.sol          # Secure contract using hashing
│
├── README.md                       # Project overview and instructions
🚀 Getting Started
You can test the contracts using Remix IDE:

Visit Remix

Create a new file and paste the contract code from SimplePassword.sol or HashedPassword.sol

Compile and deploy the contract

Use the UI to test password functionality

🔑 Example: HashedPassword.sol
solidity
Copy
Edit
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

⚠️ Security Note
This is for educational purposes only. Even hashed passwords on-chain are not entirely secure since inputs and contract code are publicly viewable. In real-world applications, use off-chain authentication or zero-knowledge proofs.

🧠 What I Learned
How to write and deploy Solidity smart contracts

The importance of not storing plaintext passwords

Basics of cryptographic hashing in Solidity

📜 License
This project is licensed under the MIT License.
