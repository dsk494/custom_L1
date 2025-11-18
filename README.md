CometBFT is one of the most widely adopted and battle-tested consensus engines in blockchain today. It is a [Byzantine Fault Tolerant (BFT)](https://en.wikipedia.org/wiki/Byzantine_fault) middleware that takes a state transition machine—written in any programming language—and securely replicates it across many machines.

CometBFT is highly performant and supports speeds of up to **10,000 transactions per second (TPS)**. Its flagship feature, **ABCI++**, enables developers to add programmability and customization to every step of the consensus engine.

Developers can use CometBFT for BFT state machine replication of applications written in any programming language or development environment. This modularity gives teams the flexibility to choose the tools best suited for their project, improves maintainability, and delivers the scalability required for large-scale decentralized applications.

---

## 🚀 Project Goal

The goal was to design an L1 with different, more performant consensus characteristics. By rewriting CometBFT using a **Rust-based consensus engine**, we can increase throughput to **~15,000 TPS**—slightly below Solana's theoretical maximum of **~65,000 TPS**, but significantly higher than standard CometBFT performance. With additional optimizations, even higher TPS may be achievable.

This project was inspired by **Hyperliquid** 🙂
