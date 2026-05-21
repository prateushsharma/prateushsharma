<div align="center">

# ⚡ Prateush Sharma

**Blockchain Engineer** · Building at the edges of EVM, ZK, and P2P networking

[![Email](https://img.shields.io/badge/email-prateushsharma@gmail.com-0f6e56?style=flat-square&logo=gmail)](mailto:prateushsharma@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-prateushsharma-0f6e56?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/prateushsharma)
[![Twitter](https://img.shields.io/badge/X-@PrateushSharma-0f6e56?style=flat-square&logo=x)](https://x.com/PrateushSharma)

</div>

---

## 👤 About Me

- 🦀 Rust-first engineer focused on **low-level blockchain infrastructure** — P2P networking, cryptographic systems, and cross-VM execution
- 🔐 Passionate about **zero-knowledge proofs** — from protocol math (Chaum-Pedersen, Sigma protocols) to production gRPC systems
- ⚙️ Contributed to **Umi Network** building cross-VM execution logic bridging MoveVM ↔ EVM and the Umi Agent Kit SDK
- 🌐 Deep interest in **Ethereum core** — studying OP Stack, PeerDAS, blob transactions, and the devp2p networking layer
- 🏗️ I build things I want to understand deeply — both projects below were written from scratch
- 🔗 Building **[ExternEVM](https://github.com/ExternEVM/ExternEVM)** — a custom EVM chain with protocol-level API precompiles, custom consensus layer, and multi-node median aggregation.

---
## 🛠 Stack

`Rust` `Solidity` `Move` `ZK Proofs` `OP Stack` `EVM` `P2P / devp2p` `gRPC` `Cairo / Starknet` `Protobuf` `KZG` `secp256k1`

## 🔬 Currently Working On
- **ExternEVM** — multi-node median aggregation via custom devp2p subprotocol, consensus layer binary over Engine API, roadmap toward commit-reveal and stake-weighted finalization
- **Blobs + PeerDAS** — EIP-4844 data availability, KZG commitments, peer sampling
- **Rust ZKP systems** — Chaum-Pedersen, Fiat-Shamir, secp256k1 implementations
- **Ethereum core internals** — devp2p, RLPx, fork detection, ENR/discv5
- **Cross-VM execution** — MoveVM ↔ EVM bridging, OP-Move design

---

## 🦀 Projects

**[ExternEVM](https://github.com/ExternEVM/ExternEVM)**
> Custom Reth-based EVM runtime where Solidity contracts call external APIs during execution — at the protocol level. Forked Reth's execution client, implemented a native precompile at 0xAA that performs real HTTP calls inside block execution, built a custom `extern/1` devp2p subprotocol for cross-node value broadcasting with median aggregation, and designed a standalone consensus layer binary over the Ethereum Engine API with JWT-authenticated round-robin PoA. Full protocol evolution from single-node direct execution through commit-reveal consensus, stake-weighted slashing, to TEE/ZK proof-of-fetch.
`Rust` `Reth` `revm` `alloy-sol-types` `devp2p` `RLPx` `Engine API` `Solidity` `reqwest` `tokio` `Docker`

**[EthNetLite](https://github.com/PrateushSharma/EthNetLite)**
> Ethereum P2P networking stack built from scratch in Rust. Implements Kademlia DHT, ENR, discv5 peer discovery, RLPx/devp2p encrypted transport, and the ETH/66 wire protocol with fork-aware handshaking.
`Rust` `Kademlia` `discv5` `RLPx` `devp2p` `async`

**[rust-zkp-chaum-pedersen](https://github.com/PrateushSharma/rust-zkp-chaum-pedersen)**
> Zero-knowledge proof authentication system implementing the Chaum-Pedersen protocol with Fiat-Shamir transform. Full gRPC client/server built with Tonic and Protobuf, using secp256k1 for the group operations.
`Rust` `ZKP` `Chaum-Pedersen` `gRPC` `Tonic` `secp256k1`

**[reth-exdiff](https://github.com/prateushsharma/reth-exdiff)**
> Reth ExDiff is a reorg-safe canonical state-diff and receipt-proof pipeline built as a native Reth Execution Extension. It tracks every account change, every storage write, and every receipt across Ethereum history — not naively by block number, but branch-aware, fork-aware, and cryptographically anchored to the canonical chain. 
`Rust` `Reth` `Ethereum` `ExEx` `staged-sync` `reorg-handling` `state-diffs` `receipt-proofs` `async`

**[AutoPool.BET](https://github.com/prateushsharma/AutoPool.BET)**
> AutoPool.BET is a revolutionary multi-chain AI-powered prediction market where pool creators compete alongside players, eliminating the house edge. Confidence-weighted rewards and cross-chain strategy execution redefine decentralized competitive betting 
`Solidity` `Chainlink` `CCIP` `Cross Chain` `AI Agent` `DeFi`

**[ZaZa](https://github.com/prateushsharma/ZaZa)**
>MCP powered No code AI Agent creator for Blockchain
`Javascript` `React` `Ai Agent` `MCP` `Smart Contract` `DeFi`
---

## 🏆 Hackathon Wins

🥇 **Agentic Ethereum — Winner Nethermind starknet track**


🥇 **BASE Wallet Risk Scoring — 1st Prize**


🥇 **Umi-try-a-thon — 1st Prize**
>

🏅 **ETH India 24- Winner multi parti computation track**


🏅 **Aleph Hackathon ×2 — Stellar Track · Citrea Track**


🏅 **Chainlink Chromium — Avalanche Track**


---

## 📄 Research & Writing

- 📝 [**D-RecSys: A Decentralized Recommendation Framework for Web 3.0-Based Content-Sharing Platforms**](https://dl.acm.org/doi/10.1145/3771093) 


---

<div align="center">
<sub>Always building. Always curious.</sub>
</div>

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=prateushsharma&label=Profile%20views%20since%20May%202026&color=0e75b6&style=flat" alt="profile views" />
</p>
