<div align="center">

# 🐾 PetLedger
**Blockchain-Based Decentralized Pet Grooming & Boarding Service Management**

[![Stellar](https://img.shields.io/badge/Network-Stellar_Soroban-blue?style=flat-square&logo=stellar)](https://stellar.org)
[![Rust](https://img.shields.io/badge/Language-Rust-orange?style=flat-square&logo=rust)](https://www.rust-lang.org/)
[![Status](https://img.shields.io/badge/Status-Testnet_Deployed-success?style=flat-square)](#contract-details)

*Securing Your Pet's Care on the Blockchain*

</div>

---

## 📖 Project Description

> **PetLedger** is a decentralized smart contract solution built on the Stellar blockchain using the Soroban SDK. It provides a secure, transparent platform for managing pet care services, specifically focusing on grooming and boarding with pick-up and drop-off tracking. 

The contract ensures that service orders and statuses are stored transparently on-chain, eliminating reliance on centralized database providers. The system allows pet owners or shop admins to request services, track order statuses in real-time, view all active requests, and cancel services. By leveraging the efficiency and security of the Stellar network, every transaction and service update is uniquely identified and reliably stored.

---

## 🚀 Project Vision

Our vision is to revolutionize the pet care service industry in the digital age by:

* 🌐 **Decentralizing Data**: Moving service logs from centralized servers to a global, distributed blockchain.
* 🔍 **Ensuring Transparency**: Providing verifiable service histories and real-time status updates (e.g., from *"Waiting for Pickup"* to *"Completed"*).
* 🔒 **Guaranteeing Immutability**: Providing a permanent, tamper-proof record of transactions and pet care histories.
* 🤝 **Enhancing Trust**: Building a trustless system where agreements between pet owners and service providers are guaranteed by code.

---

## ✨ Key Features

* 📝 **Simple Service Request**: Create grooming or boarding orders with one function call. Stores essential data (Owner, Pet Name, Service Type, Address) with automated ID generation.
* ⏱️ **Real-Time Status Tracking**: Update the status of each service seamlessly as it progresses, providing transparency for pet owners.
* 📥 **Efficient Data Retrieval**: Fetch all active and past service requests in a single call, structured for easy frontend integration.
* 🗑️ **Secure Cancellation**: Remove specific service requests using their unique IDs for clean storage management.
* ⚡ **Stellar Integration**: Leverages the high speed and low cost of Stellar, built using the modern Soroban SDK.

---

## 🔗 Contract Details

| Network | Contract ID |
| :--- | :--- |
| **Testnet** | `CAWJ7DOWG443REITUBE6TAEH3MUEOJVXIJ3XHU3OAODK5YDAB5CKMTKW` |

---

## 🛠️ Getting Started

### Technical Requirements
* Soroban SDK
* Rust programming language
* Stellar blockchain network

### Core Functions
Deploy the smart contract to Stellar's Soroban network and interact with it using these main functions:

| Function | Description |
| :--- | :--- |
| `request_service()` | Create a new grooming/boarding order with pet and owner details. |
| `update_status()` | Change the progress status of a specific order by its ID. |
| `get_services()` | Retrieve all stored service requests from the contract. |
| `cancel_service()` | Remove or cancel a specific service order by its ID. |

---

## 🔮 Future Scope

<details>
<summary><b>Click to view Short-Term Enhancements</b></summary>
<br>
1. <b>Medical & Vaccine Records</b>: Store immutable vaccination and allergy records for each pet.<br>
2. <b>Category & Pricing Management</b>: Add dynamic pricing based on pet size and selected service packages.<br>
3. <b>Search & Filter</b>: Implement advanced search filters (by owner name or specific status) for the admin dashboard.
</details>

<details>
<summary><b>Click to view Medium-Term Development</b></summary>
<br>
4. <b>On-Chain Payments</b>: Integrate Stellar USDC or native XLM for automated payment upon service completion.<br>
5. <b>Notification System</b>: Off-chain bridge to alert users via email/SMS when their pet is picked up or ready to go home.<br>
6. <b>Customer Loyalty Program</b>: Issue tokens or digital badges to frequent customers for discounts.
</details>

<details>
<summary><b>Click to view Long-Term Vision & Enterprise Features</b></summary>
<br>
7. <b>Pet Identity NFTs</b>: Mint a unique, verifiable NFT for every pet registered in the system containing their full history.<br>
8. <b>Decentralized UI Hosting</b>: Host the frontend on IPFS or similar decentralized platforms.<br>
9. <b>Multi-Branch Synchronization</b>: Expand the contract logic to support multiple pet shop branches under one franchise.<br>
10. <b>Inter-Contract Integration</b>: Allow vet clinics or pet insurance smart contracts to interact with the PetCare DApp data.<br>
11. <b>Immutable Auditing</b>: Create time-locked logs for employee performance and shop revenue audits.<br>
12. <b>Automated Reporting</b>: Automatic daily/weekly summary triggers for shop managers.
</details>

---

## 📸 Testnet Deployment Screenshots

**Stellar Block Explorer Profile:**
<br>
![Stellar Explorer Profile](stellar-explorer-contract.png)
<br>

**Contract Deployment:**
<br>
![Deploy Screenshot](testnet-deploy.png)
<br>

**Function Execution:**
<br>
![Invoke Screenshot](testnet-invoke.png)