# Blockchain_Simulation
Overview

This is a simple blockchain simulation implemented in Java. It demonstrates the core concepts of blockchain technology, including blocks, transactions, mining, and chain validation.

Features

SHA-256 hashing for block security

Proof-of-work mining mechanism

Block tampering demonstration with validation

Simple transaction processing

Prerequisites

Make sure you have the following installed:

Java Development Kit (JDK) 11 or later

Setup and Execution

Clone the Repository

git clone https://github.com/Tasfiya113/Java-Blockchain-Simulation.git
cd Java-Blockchain-Simulation

Compile and Run the Program

javac BlockchainSimulation.java
java BlockchainSimulation

Code Structure

Block.java - Defines the Block class, including hashing and mining logic.

Blockchain.java - Manages the blockchain, adding blocks, and validating integrity.

BlockchainSimulation.java - Main class to simulate transactions and demonstrate blockchain functionality.

Example Output

Blockchain before tampering:
Block 0 {
  Timestamp: 1700000000000
  Transactions: [Genesis Block]
  Previous Hash: 0
  Hash: abcd1234...
}
...
Is blockchain valid? true

Blockchain after tampering:
...
Is blockchain valid? false

License

This project is licensed under the MIT License.

Author

[Tasfiya]

