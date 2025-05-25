# 🏦 Multithreaded Banking System in Java

This Java project simulates a multi-threaded banking system where multiple users (threads) can perform deposit and withdrawal transactions on a shared bank account simultaneously. The system uses thread synchronization to avoid race conditions and ensure safe transactions.

---

## 🚀 Features

- Shared bank account with thread-safe operations
- Synchronized `deposit` and `withdraw` methods
- Concurrent transactions via Java threads
- Input from the user for account balance and transaction list
- Final account balance displayed after all transactions

---

## 📂 Project Structure

```bash
MultithreadedBanking/
├── Main.java         # Main program to run the simulation
├── BankAccount.java  # Class representing the shared bank account
├── UserThread.java   # Class simulating a user performing a transaction
└── README.md         # Project documentation
