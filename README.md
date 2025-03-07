# Yacoin: A Simple Proof-of-Work Cryptocurrency

Welcome to Yacoin – a minimalistic, educational cryptocurrency implemented from scratch! This project demonstrates the fundamental principles behind blockchain-based digital currencies, focusing on Proof-of-Work (PoW) and SHA-256 hashing.

# 🏗️ Core Components

Yacoin is built around the essential components of a cryptocurrency:

### 1. 🧩 Block

Each block in Yacoin contains:

* Index: The block number in the chain. 
* Timestamp: When the block was created. 
* Transactions: A list of mock transactions. 
* Previous Block Hash: Links this block to the chain. 
* Nonce: A number adjusted to satisfy mining conditions. 
* Hash: The unique SHA-256 hash of the block.

### 2. 🔗 Blockchain

A series of blocks linked together, ensuring immutability. The first block (genesis block) starts the chain, and new blocks are mined through PoW.

### 3. ⛏️ Proof-of-Work (PoW)

To add a new block, miners must find a valid nonce that makes the block hash meet a difficulty requirement (e.g., leading zeros). This secures the network by making mining computationally expensive.

### 4. 📜 Transactions

Yacoin simplifies transactions to basic sender/receiver/value structures. Transactions are grouped into blocks before being mined.

### 5. 🏛️ Consensus

The longest valid chain is considered the true blockchain. Nodes sync to this rule to maintain integrity.

### 6. 🌍 P2P Network

Yacoin operates on a peer-to-peer (P2P) network where nodes communicate directly. Each node:

* Maintains a copy of the blockchain. 
* Broadcasts new transactions and blocks. 
* Validates received blocks before adding them. 
* Ensures consensus by adopting the longest valid chain.

Nodes discover and connect to peers dynamically, propagating updates efficiently across the network.

# 🚀 Getting Started

Want to play around with Yacoin? Clone this repository and start mining blocks!

## Clone the repo
```sh
git clone https://github.com/aal89/yacoin.git
cd yacoin
```

## Build and run (using Gradle)
```sh
./gradlew run
```

# 📚 Learning Objectives

By working with Yacoin, you’ll gain a deeper understanding of:  
✅ How blockchain structures work.  
✅ How PoW secures a network.  
✅ How SHA-256 hashing links blocks.  
✅ How transactions are batched into blocks.  
✅ The basics of consensus mechanisms.  
✅ How a P2P network propagates data.

# 🤝 Contributing

This is a learning project! Feel free to open issues or submit pull requests to improve Yacoin.

Happy mining! ⛏️💎

