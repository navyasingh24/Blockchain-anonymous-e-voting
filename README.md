# Blockchain-anonymous-e-voting
Privacy preserving and verifiable E-Voting System using Commit–Reveal Scheme on a Permissioned Ethereum Network


This project implements a **permissioned blockchain-based e-voting system** with a **commit–reveal scheme** to ensure **full voter anonymity**, **end-to-end verifiability**, and prevention of double voting. It is built using **Solidity** and deployed on a private Ethereum network.

---

## Features

- **Permissioned Blockchain** – Only authorized nodes participate in block validation.
- **Commit–Reveal Scheme** – Ensures votes remain private until the reveal phase.
- **Double Voting Prevention** – Each voter can cast only one valid vote.
- **End-to-End Verifiability** – Every vote is recorded transparently on-chain.
- **Smart Contract-Based** – Fully decentralized logic using Solidity.
- **Easily Deployable** – Compatible with Remix, Hardhat, and private Ethereum networks.

---

## Technology Stack

- **Solidity** (Smart Contracts)
- **Ethereum (Geth) PoA Network**
- **Remix IDE** (Smart contract deployment)
- **Web3.js** (Optional interaction)
- **GitHub Pages** (Code repository)
  
---

## Quick Start (Remix IDE)

1. Open [Remix IDE](https://remix.ethereum.org/).
2. Import this repository:
   - Click **File Explorers → GitHub → Clone** and paste your repo URL:
     ```
     https://github.com/navyasingh24/Blockchain-anonymous-e-voting.git
     ```
3. Open the `AdvancedVoting.sol` (or your main contract).
4. Compile the contract using the **Solidity Compiler** (e.g., 0.8.x).
5. Deploy using:
   - **Injected Provider / Local Network** (if using Geth).
   - Or **Remix VM** for quick testing.

---

## System Workflow

1. **Commit Phase:** Voters submit a hash of their vote + secret.
2. **Reveal Phase:** Voters reveal their vote + secret, which is verified against the commit.
3. **Tally:** Contract automatically counts valid votes.

---


---

## License
This project is licensed under the **MIT License** – free to use and modify.

---

## Author
**Navya Singh**  
BTech CSE – Manipal University Jaipur  

---


