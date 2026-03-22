# RoadChain

Layer-1 blockchain built from scratch in Python. Real cryptography, real consensus, real blocks.

## What It Does

RoadChain is a working blockchain with SHA-256 proof-of-work, secp256k1 ECDSA signatures, Merkle trees, and Bitcoin-compatible block headers. Includes a wallet CLI for key generation, transactions, and mining.

## Features

- **Proof of Work** — SHA-256 mining with adjustable difficulty
- **ECDSA signatures** — secp256k1 curve (same as Bitcoin)
- **Merkle trees** — transaction integrity verification
- **Bitcoin-compatible headers** — standard 80-byte block header format
- **Wallet CLI** — generate keys, send transactions, check balances
- **P2P networking** — connect nodes into a network

## Wallet CLI

```bash
python roadchain.py wallet create          # Generate a new keypair
python roadchain.py wallet balance <addr>  # Check balance
python roadchain.py tx send <to> <amount>  # Send a transaction
python roadchain.py mine                   # Start mining blocks
python roadchain.py node start             # Run a full node
```

## Block Structure

Each block contains:
- Previous block hash (chain linkage)
- Merkle root of all transactions
- Timestamp and nonce (proof of work)
- Difficulty target
- Transaction list with ECDSA signatures

## Stack

- **Language**: Python 3
- **Crypto**: secp256k1 (ECDSA), SHA-256, RIPEMD-160
- **Storage**: Local chain data files
- **Network**: P2P node communication

## Run

```bash
pip install -r requirements.txt
python roadchain.py node start    # Start a node
python roadchain.py mine          # Mine blocks
```

## Why From Scratch

No frameworks. No shortcuts. Every hash, signature, and consensus rule is written and understood line by line. If you want to know how a blockchain actually works, read this code.

## License

Proprietary. Copyright (c) 2024-2026 BlackRoad OS, Inc. All rights reserved.

---

*Remember the Road. Pave Tomorrow.*
