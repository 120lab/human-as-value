# human-as-value

# env

Write Smart contract BEP-20
Deploy TO-Testnet
Verify IN BscScan
Contact to DEX (PancakeSwap)
Tokenomics + Audit



# BEP-20 Development Environment Setup (Binance Smart Chain)

This guide explains how to set up a **professional development environment** for writing, testing, and deploying **BEP-20 smart contracts** on **Binance Smart Chain (BSC)**.

The setup is suitable for production-grade projects and future smart-contract audits.

---

## 🎯 Purpose

The environment allows you to:

- Write smart contracts in **Solidity**
- Compile, test, and deploy **BEP-20 tokens**
- Interact securely with **Binance Smart Chain**
- Prepare contracts for **verification and audit**

---

## 🧱 Technology Stack

- **Node.js** – JavaScript runtime
- **Hardhat** – Smart contract development framework
- **Solidity** – Smart contract language
- **OpenZeppelin** – Audited contract libraries
- **MetaMask** – Wallet for deployment
- **BSC RPC** – Blockchain connection

---

## 1️⃣ Install Node.js (Required)

Recommended version: **Node 18 LTS or Node 20 LTS**

Download and install:  
https://nodejs.org

Verify installation:
```bash
node -v

npm -v

if can't see npm version run Powershell script
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
