# Pharma Chain / Hyperledger Fabric

## 🔗 Repository

- Original repo: https://github.com/dteti-sys-rsch/pharma-chain

## 🔑 Backend Keywords

Hyperledger Fabric, IPFS, REST APIs, off-chain databases, Docker, benchmarking, interoperability, distributed systems, backend infrastructure, healthcare data exchange

## 🧾 Overview

Healthcare supply-chain interoperability prototype built with Hyperledger Fabric.

The project explored secure data exchange between hospital and insurance networks using a distributed backend architecture.

## 🛠️ My Role

- Blockchain Researcher Intern
- Focused on backend infrastructure, cross-chain flows, IPFS, and off-chain data integration

## ❗ Problem

The system needed a testbed for secure interoperability between distinct blockchain networks without overloading the ledger with large data.

### 🧩 Sub-Problem: cross-network interoperability

- Problem: hospital and insurance networks needed to exchange data securely.
- Solution: built a cross-network application flow around Hyperledger Fabric.
- Stack: Hyperledger Fabric, REST APIs, off-chain databases.
- Result: two networks could work together in a controlled testbed.

### 🧩 Sub-Problem: ledger size and data storage

- Problem: large data could not live directly on-chain.
- Solution: used IPFS and off-chain storage for heavy data.
- Stack: IPFS, off-chain databases, Docker.
- Result: a more efficient distributed architecture.

## 🧰 Stack

- Hyperledger Fabric
- REST APIs
- IPFS
- Off-chain databases
- Docker
- Benchmarking tools

## Architecture / Flow

- Two separate Hyperledger Fabric networks
- Cross-network application flow for hospital and insurance scenarios
- IPFS for decentralized file storage
- Off-chain database integration for operational data
- Benchmarking with load and performance measurement tools

## 📈 Result / Impact

- Built **2 independent Hyperledger Fabric networks**
- Configured **6 organizations**
- Coordinated **30+ Docker containers**

## ✅ Solution

- Split the prototype into two Fabric networks
- Added off-chain data handling for large or heavy content
- Used IPFS for decentralized storage and backend traceability

## 🖼️ Evidence

### 🎥 Demo / Video

- Demo GIF: _add link or embed_
- YouTube / Loom: _add link or embed_

### 🏗️ Architecture

- Architecture diagram: _add link or embed_
- Flow diagram: _add link or embed_

### 🗃️ Data Model

- ERD: _add link or embed_

### 💻 Code / Pattern

- Code snippet: _add link or embed_
- Architecture pattern: on-chain verification with off-chain storage

### 📊 Metrics

- 2 independent Hyperledger Fabric networks
- 6 organizations configured
- 30+ Docker containers

## ⚠️ Challenges

- Coordinating multiple blockchain networks cleanly
- Keeping data movement efficient across on-chain and off-chain layers
- Managing infrastructure complexity without losing traceability

## 💡 What I Learned

- Distributed systems need clear boundaries between verification and storage
- Blockchain prototypes still need strong backend discipline
- Infrastructure design is part of product design
