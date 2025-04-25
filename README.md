# Blockchain-Based Voting System

A decentralized voting system built with *Solidity, **React, **Node.js, and **Ethereum* (via Ganache). This DApp ensures secure, transparent, and tamper-proof elections using blockchain technology.

---

## Features

- *User Authentication with MetaMask*
- *Immutable and Secure Vote Recording*
- *Real-Time Result Tallying*
- *Modern UI for Smooth Voting Experience*

---

## Tech Stack

| Layer       | Tech                          |
|------------|-------------------------------|
| Smart Contract | Solidity, Truffle         |
| Frontend    | React, Web3.js, Bootstrap    |
| Backend     | Node.js (used internally by Truffle) |
| Blockchain  | Ganache (Local Ethereum Node) |

---

## Project Structure
Blockchain-Voting-System/ │ ├── contracts/ │   └── Voting.sol                # Smart contract for voting │ ├── migrations/ │   └── 1_deploy_contracts.js     # Truffle migration script │ ├── build/ │   └── contracts/ │       └── Voting.json           # ABI file generated after compilation │ ├── client/ │   ├── public/ │   │   └── index.html │   ├── src/ │   │   ├── contracts/ │   │   │   └── Voting.json       # ABI copied here after migration │   │   ├── App.js │   │   └── index.js │   ├── package.json │   └── ... │ ├── truffle-config.js └── README.md

---

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14+ recommended)
- [Truffle](https://trufflesuite.com/truffle/)
- [Ganache](https://trufflesuite.com/ganache/)
- [MetaMask](https://metamask.io/) extension in browser

---
