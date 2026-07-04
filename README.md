# 🚀 MemberDAO – Decentralized Governance & Voting System

A fully decentralized DAO governance platform built with **Solidity**, **Hardhat**, **ethers.js**, and a lightweight **HTML/CSS/JavaScript** frontend.

This project demonstrates how decentralized organizations can securely manage members, create governance proposals, and conduct transparent on-chain voting through smart contracts.

---

## ✨ Key Features

* 🔐 Secure DAO member management
* 🗳️ Create governance proposals
* ✅ Vote **YES** or **NO** on proposals
* 🛡️ One wallet = One vote per proposal
* ⏳ Time-limited voting period
* ⚡ Execute proposals after the voting deadline
* 🦊 MetaMask integration
* 🌐 Simple and responsive web interface
* ⛓️ Fully on-chain governance logic
* 📜 Transparent and immutable voting records

---

## 🛠️ Tech Stack

* Solidity
* Hardhat
* ethers.js
* JavaScript (ES6)
* HTML5
* CSS3
* MetaMask
* Ethereum

---

## 📂 Project Overview

**MemberDAO** is a decentralized governance application designed to demonstrate secure and transparent DAO voting mechanisms.

The core smart contract (**MemberDAO.sol**) enables the contract owner to manage DAO membership by adding or removing members. Only verified members are authorized to create proposals and participate in governance voting.

To ensure election integrity, the contract strictly enforces a **one-address, one-vote-per-proposal** policy, preventing duplicate voting and maintaining fairness.

Each proposal includes a predefined voting deadline. Once the voting period expires, eligible proposals can be executed directly on-chain according to the recorded voting outcome.

The frontend communicates with the Ethereum blockchain through **MetaMask** and **ethers.js**, allowing users to:

* Connect their wallet
* Verify DAO membership
* Create governance proposals
* Cast votes securely
* View proposal status in real time

This project highlights the core principles of decentralized governance, including **transparency, security, immutability, and trustless decision-making**, while providing a practical example of blockchain-based DAO implementation.

---

## 📦 Installation

```bash
npm install
```

---

## 🎯 Learning Objectives

This project demonstrates practical experience with:

* Smart Contract Development
* DAO Governance Architecture
* Ethereum Wallet Integration
* Blockchain Security Principles
* Decentralized Voting Systems
* Web3 Frontend Development
* Hardhat Development Environment
* ethers.js Interaction Layer
