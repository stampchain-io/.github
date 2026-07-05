<div align="center">

# Bitcoin Stamps

**Unprunable data storage on Bitcoin's UTXO set. Permanent by design.**

[![Docs](https://img.shields.io/badge/docs-bitcoinstamps.xyz-F7931A?logo=bitcoin&logoColor=white)](https://bitcoinstamps.xyz)
[![Explorer](https://img.shields.io/badge/explorer-stampchain.io-F7931A?logo=bitcoin&logoColor=white)](https://stampchain.io)
[![API Docs](https://img.shields.io/badge/API-OpenAPI%2FSwagger-4c8dbf)](https://stampchain.io/docs)
[![Telegram](https://img.shields.io/badge/community-Telegram-26A5E4?logo=telegram&logoColor=white)](https://t.me/BitcoinStamps)

</div>

Bitcoin Stamps embed data directly in Bitcoin transactions using bare multisig outputs, storing it in the UTXO set where node operators cannot prune it. Every stamp is a permanent on-chain artifact, secured by Bitcoin itself with no off-chain dependencies.

The protocol was created by [mikeinspace](https://x.com/mikeinspace), with co-founders Arwyn and Reinamora. The community mascot is KEVIN, the first SRC-20 token.

**stampchain-io** is the protocol and indexer home: the reference indexer, the public API and block explorer, and the protocol specifications live here. Client libraries and developer tooling live in the sibling [**btc-stamps**](https://github.com/btc-stamps) organization.

### Protocols

| Standard | What it does |
|----------|--------------|
| **SRC-20** | Fungible tokens stamped directly onto Bitcoin |
| **SRC-101** | Decentralized naming system |
| **SRC-721** | Non-fungible token standard for Stamps |
| **SRC-721r** | Recursion: stamps that reference and compose other stamps |
| **OLGA** | P2WSH encoding optimization for all stamp protocols |

### Core Infrastructure

| Repository | Description |
|------------|-------------|
| [**btc_stamps**](https://github.com/stampchain-io/btc_stamps) | Indexer: parses and indexes all Bitcoin Stamps transactions |
| | [![Code Quality](https://img.shields.io/github/actions/workflow/status/stampchain-io/btc_stamps/python-check.yml?label=Code%20Quality&job=code-quality&branch=main)](https://github.com/stampchain-io/btc_stamps/actions/workflows/python-check.yml) [![Integration](https://img.shields.io/github/actions/workflow/status/stampchain-io/btc_stamps/python-check.yml?label=Integration&job=integration&branch=main)](https://github.com/stampchain-io/btc_stamps/actions/workflows/python-check.yml) [![codecov](https://img.shields.io/codecov/c/github/stampchain-io/btc_stamps?label=codecov)](https://codecov.io/gh/stampchain-io/btc_stamps) |
| [**stampchain.io**](https://github.com/stampchain-io/stampchain.io) | API and Explorer: public REST API and block explorer at [stampchain.io](https://stampchain.io) |
| | [![Code Quality](https://github.com/stampchain-io/stampchain.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/stampchain-io/stampchain.io/actions/workflows/deploy.yml) [![Unit Tests](https://github.com/stampchain-io/stampchain.io/actions/workflows/unit-tests.yml/badge.svg)](https://github.com/stampchain-io/stampchain.io/actions/workflows/unit-tests.yml) [![Newman API](https://github.com/stampchain-io/stampchain.io/actions/workflows/newman-comprehensive-tests.yml/badge.svg)](https://github.com/stampchain-io/stampchain.io/actions/workflows/newman-comprehensive-tests.yml) |
| [**tx-builder**](https://github.com/btc-stamps/tx-builder) | Transaction Builder: Bitcoin Stamps and SRC-20 transaction library ([NPM](https://www.npmjs.com/package/@btc-stamps/tx-builder) · [JSR](https://jsr.io/@btc-stamps/tx-builder)) |
| | [![Node.js CI](https://img.shields.io/github/actions/workflow/status/btc-stamps/tx-builder/ci.yml?branch=main)](https://github.com/btc-stamps/tx-builder/actions) [![codecov](https://img.shields.io/codecov/c/github/btc-stamps/tx-builder?label=codecov)](https://codecov.io/gh/btc-stamps/tx-builder) [![npm](https://img.shields.io/npm/v/@btc-stamps/tx-builder.svg)](https://www.npmjs.com/package/@btc-stamps/tx-builder) |
| [**stamps_sdk**](https://github.com/stampchain-io/stamps_sdk) | SDK: TypeScript library for building with Bitcoin Stamps |
| [**stampchain-mcp**](https://github.com/stampchain-io/stampchain-mcp) | MCP Server: AI integration via Model Context Protocol |

### Protocol Specifications

| Standard | Description |
|----------|-------------|
| [**stamps**](https://github.com/stampchain-io/stamps) | Bitcoin Stamps Protocol Definition |
| [**src-721**](https://github.com/stampchain-io/src-721) | SRC-721 non-fungible token standard for Stamps |
| [**src721r-example**](https://github.com/stampchain-io/src721r-example) | SRC-721r recursive token example |
| [**Glyphs**](https://github.com/stampchain-io/Glyphs) | Fungible token meta-protocol built on Counterparty |

### Documentation & Governance

| Resource | Link |
|----------|------|
| Protocol Documentation | [bitcoinstamps.xyz](https://bitcoinstamps.xyz) (guides, tutorials, and protocol specs; [source repo](https://github.com/btc-stamps/bitcoinstamps.xyz)) |
| Technical Whitepaper | [bitcoinstamps.xyz/en/whitepaper](https://bitcoinstamps.xyz/en/whitepaper/) · [Source](https://github.com/stampchain-io/btc_stamps/tree/main/docs/whitepaper) |
| SIP Roadmap & Registry | [bitcoinstamps.xyz/en/protocols/sips](https://bitcoinstamps.xyz/en/protocols/sips) |
| SIP Process (SIP-0000) | [GitHub Issue #686](https://github.com/stampchain-io/btc_stamps/issues/686) |
| API Documentation | [stampchain.io/docs](https://stampchain.io/docs) (OpenAPI/Swagger reference) |

### Prominent Users of the Bitcoin Stamps Indexer & API

[KuCoin](https://x.com/kucoincom) · [SuperEx](https://x.com/SuperExet) · [OpenStamp](https://x.com/btcOpenStamp) · [Leather Wallet](https://x.com/LeatherBTC)

---

<div align="center">

Built with Bitcoin. Permanent by design. 🧡

</div>
