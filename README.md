# Hi, I'm Daniel Zhou

Blockchain engineer specializing in **smart contracts, DeFi protocols, wallet infrastructure, and MPC signing**. I have 3 years of experience building Web3 backend and smart contract systems with Solidity and Go.

## What I Work On

- **Prediction markets:** CLOB matching with price-time priority, YES/NO mirrored liquidity, and automated market making with inventory and risk controls.
- **Wallet infrastructure:** Multichain exchange wallets covering deposits, withdrawals, fund sweeping, offline signing, and chain-reorganization recovery across account and UTXO chains.
- **MPC signing:** Distributed ECDSA/EdDSA key generation and signing, P2P communication, fault attribution, and secure key-share storage.
- **DeFi protocols:** Cross-chain staking, reward distribution, bridge contracts, and proof-of-stake smart contracts.

## Selected Projects

### [MPC Threshold Signature Services](https://github.com/Sandwichzzy/MPC-TSS)

Co-designed distributed KeyGen and KeySign using Go, `bnb-chain/tss-lib`, `libp2p`, and WebSockets. Key shares remain on participating nodes or in controlled storage; the full private key is never assembled. The service supports local storage, AWS Secrets Manager, and a mode combining Shamir sharding with KMS encryption and distributed storage.

### [Multichain Wallet Middleware Services](https://github.com/Sandwichzzy/exchange-wallet-services)

Built a Go and gRPC wallet platform for chain scanning, deposits, withdrawals, sweeping, hot/cold transfers, offline signing, broadcasting, and risk checks. Unified RPC and scanning interfaces support EVM-style account chains and BTC-style UTXO chains, with resumable checkpoints and reorganization repair.

### [Cross-Chain Staking Protocol](https://github.com/Sandwichzzy/Crosschain-Staking-Contract)

Developed L1/L2 staking and bridge contracts, staking-derivative minting, and reward distribution. The protocol combines Ethereum validator rewards, L2 incentives, and restaking yield, with oracle verification, pause controls, and reentrancy protection.

### Cross-Chain Bridge Components

- [Bridge Contracts](https://github.com/Sandwichzzy/Bridge-Contracts): Pool-based cross-chain asset bridge contracts.
- [Relayer Node](https://github.com/Sandwichzzy/relayer-node): Cross-chain data synchronization service.
- [Gas Oracle](https://github.com/Sandwichzzy/gas-oracle): gRPC service for EVM-chain gas fee synchronization.

## Technical Skills

- **Languages:** Solidity, Go, TypeScript; basic Rust.
- **Web3:** Foundry, OpenZeppelin, ethers.js, web3.js; fuzz, unit, and integration testing.
- **Backend:** gRPC, MySQL, PostgreSQL, Redis, Kafka.
- **Cryptography:** ECDSA/EdDSA, Shamir Secret Sharing, MPC, BLS signatures.
- **Protocol knowledge:** Uniswap V2/V3, Aave V3, EigenLayer, cross-chain staking, and prediction markets.

## Contact

[Email](mailto:danielsandwich59@gmail.com) · [GitHub](https://github.com/Sandwichzzy) · [Telegram](https://t.me/SandwichZZY)
