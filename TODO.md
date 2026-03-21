# RoadChain — TODO

## [RC] Smart Contracts
- [ ] [RC] Deploy ConsentManager.sol to testnet
- [ ] [RC] Deploy AuditTrail.sol with Merkle proof generation
- [ ] [RC] Deploy IdentityOracle.sol with DID:road method
- [ ] [RC] Deploy ComplianceGate.sol with KYC/AML rules
- [ ] [RC] Deploy DocumentRegistry.sol with IPFS integration
- [ ] [RC] Deploy ZKVerifier.sol with Groth16 + PLONK support
- [ ] [RC] Deploy MultiSigGovernance.sol (M-of-N)
- [ ] [RC] Deploy AccessRegistry.sol with RBAC
- [ ] [RC] Deploy TimeLock.sol with 24h minimum delay
- [ ] [RC] Deploy DataVault.sol with threshold encryption
- [ ] [RC] Deploy EventBus.sol for cross-contract events
- [ ] [RC] Deploy UpgradeProxy.sol (UUPS pattern)
- [ ] [RC] Full contract audit — all 12 contracts

## [RC] Zero-Knowledge Proofs
- [ ] [RC] Build Circom circuits for age verification
- [ ] [RC] Build Circom circuits for balance verification
- [ ] [RC] Build Circom circuits for membership proof
- [ ] [RC] Integrate snarkjs for client-side proof generation
- [ ] [RC] Benchmark proof generation time on Pi hardware

## [RC] Consensus & Network
- [ ] [RC] Configure Clique PoA with 5 validators
- [ ] [RC] Set 2-second block time
- [ ] [RC] Deploy JSON-RPC on :8545
- [ ] [RC] Deploy WebSocket on :8546
- [ ] [RC] Deploy GraphQL on :8547
- [ ] [RC] WireGuard mesh between validator nodes
- [ ] [RC] Tor hidden service for anonymous access

## [RC] Compliance
- [ ] [RC] GDPR consent lifecycle tests
- [ ] [RC] CCPA opt-out enforcement tests
- [ ] [RC] HIPAA PHI isolation verification
- [ ] [RC] SOX audit trail integrity tests
- [ ] [RC] SOC 2 Type II control mapping
- [ ] [RC] ISO 27001 control alignment

## [RC] Infrastructure
- [ ] [RC] PostgreSQL indexer for chain queries
- [ ] [RC] IPFS node for document storage
- [ ] [RC] MinIO integration for binary attachments
- [ ] [RC] REST API server (Express/Fastify)
- [ ] [RC] Event streaming via WebSocket subscriptions
- [ ] [RC] Monitoring dashboard (Grafana)

## [RC] Documentation
- [ ] [RC] Contract ABI documentation
- [ ] [RC] REST API reference (OpenAPI 3.0)
- [ ] [RC] Deployment guide (single node + multi-node)
- [ ] [RC] ZKP circuit authoring guide
- [ ] [RC] Compliance mapping document
