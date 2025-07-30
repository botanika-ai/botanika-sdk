# Botanika SDK

Official software development kits (SDKs) for interacting with the Botanika ecosystem.

## Overview

Botanika SDK provides programmatic access to Botanika's core systems:

- **zk-STARK Layer 2 (ZK-L2) network** - Zero-knowledge proof scaling solution
- **Node proof submission and mining** - Proof of Space Allocation (PoSA), Proof of Space Time (PoST), Proof of Erasure (PoEr)
- **On-chain staking and reward tracking** - Stake management and reward distribution
- **Governance participation** - Proposal voting and submission
- **Cross-chain bridge and token flows** - Multi-chain interoperability

## Planned SDK Packages

| SDK Name | Language/Platform | Purpose |
|----------|------------------|---------|
| `@botanika/sdk-ts` | TypeScript (NPM) | Web dApps, frontend tools, node dashboards |
| `@botanika/sdk-rust` | Rust (CLI/Binary) | CLI tools, embedded node integrations, server-side proof submission |
| `@botanika/sdk-python` | Python | Data science integrations, testing, off-chain verification |

## Project Structure

```
botanika-sdk/
├── README.md                  # Project overview and roadmap
├── .gitignore
├── docs/                      # Documentation and specifications
│   ├── ARCHITECTURE.md        # System architecture overview
│   ├── API_SPECIFICATION.md   # API interfaces and types
│   ├── ROADMAP.md            # Detailed development phases
│   └── SECURITY.md           # Security considerations and best practices
├── sdk-ts/                   # TypeScript SDK (future)
│   ├── package.json
│   ├── src/
│   └── examples/
├── sdk-rust/                 # Rust SDK (future)
│   ├── Cargo.toml
│   ├── src/
│   └── examples/
└── sdk-python/               # Python SDK (future)
    ├── setup.py
    ├── src/
    └── examples/
```

## Development Roadmap

### Phase 0: Foundation (Current)
- [x] Establish repository structure
- [x] Define SDK architecture and interfaces
- [x] Create documentation framework

### Phase 1: Proof Submission API
- [ ] Core proof submission interfaces
- [ ] PoSA, PoST, PoEr proof handling
- [ ] Proof validation and verification
- [ ] Node integration examples

### Phase 2: On-chain Staking SDK
- [ ] Stake/unstake operations
- [ ] Staking multiplier calculations
- [ ] Reward rate queries
- [ ] Staking position management

### Phase 3: Reward Tracking
- [ ] Reward snapshot fetching
- [ ] Claim history tracking
- [ ] Reward flow analysis
- [ ] Historical data queries

### Phase 4: Governance API
- [ ] Proposal reading and parsing
- [ ] Voting mechanisms
- [ ] Proposal submission
- [ ] Governance state queries

### Phase 5: L2 Transaction Interface
- [ ] zk-transaction creation
- [ ] Botanika zk-L2 interaction
- [ ] Cross-chain bridge operations
- [ ] Token transfer utilities

## Security Considerations

The Botanika SDK will implement strict validation for:

- Canonical JSON encoding standards
- ed25519 signature verification
- On-chain state synchronization before transactions
- Gas/fee simulation for EVM-compatible L2 operations

## Getting Started

This repository is currently in the planning phase. SDK packages will be released as development progresses through the roadmap phases.

For detailed specifications and architecture information, see the [docs/](docs/) directory.

## Contributing

Development guidelines and contribution processes will be established as the project moves into active development phases.

## License

See [LICENSE](LICENSE) for details.
