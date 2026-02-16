# Bitcoin Stamps

**Unprunable data storage on the Bitcoin blockchain.**

Bitcoin Stamps are a protocol for embedding data directly in Bitcoin transactions using bare multisig outputs, ensuring permanent on-chain storage that cannot be pruned by node operators. Created by [Mike In Space](https://x.com/mikeinspace).

---

### Core Infrastructure

| Repository | Description |
|------------|-------------|
| [**btc_stamps**](https://github.com/stampchain-io/btc_stamps) | Indexer — parses and indexes all Bitcoin Stamps transactions |
| | [![Code Quality](https://img.shields.io/github/actions/workflow/status/stampchain-io/btc_stamps/python-check.yml?label=Code%20Quality&job=code-quality&branch=dev)](https://github.com/stampchain-io/btc_stamps/actions/workflows/python-check.yml) [![Integration](https://img.shields.io/github/actions/workflow/status/stampchain-io/btc_stamps/python-check.yml?label=Integration&job=integration&branch=dev)](https://github.com/stampchain-io/btc_stamps/actions/workflows/python-check.yml) [![codecov](https://codecov.io/gh/stampchain-io/btc_stamps/graph/badge.svg?token=OB2OS37L5H)](https://codecov.io/gh/stampchain-io/btc_stamps) |
| [**BTCStampsExplorer**](https://github.com/stampchain-io/BTCStampsExplorer) | API & Explorer — public REST API and block explorer at [stampchain.io](https://stampchain.io) |
| | [![Code Quality](https://github.com/stampchain-io/BTCStampsExplorer/actions/workflows/deploy.yml/badge.svg)](https://github.com/stampchain-io/BTCStampsExplorer/actions/workflows/deploy.yml) [![Unit Tests](https://github.com/stampchain-io/BTCStampsExplorer/actions/workflows/unit-tests.yml/badge.svg)](https://github.com/stampchain-io/BTCStampsExplorer/actions/workflows/unit-tests.yml) [![Newman API](https://github.com/stampchain-io/BTCStampsExplorer/actions/workflows/newman-comprehensive-tests.yml/badge.svg)](https://github.com/stampchain-io/BTCStampsExplorer/actions/workflows/newman-comprehensive-tests.yml) [![codecov](https://codecov.io/gh/stampchain-io/BTCStampsExplorer/graph/badge.svg?token=4AEWJ1OMM2)](https://codecov.io/gh/stampchain-io/BTCStampsExplorer) |
| [**tx-builder**](https://github.com/btc-stamps/tx-builder) | Transaction Builder — Bitcoin Stamps & SRC-20 transaction library ([NPM](https://www.npmjs.com/package/@btc-stamps/tx-builder) · [JSR](https://jsr.io/@btc-stamps/tx-builder)) |
| | [![Node.js CI](https://img.shields.io/github/actions/workflow/status/btc-stamps/tx-builder/ci.yml?branch=main)](https://github.com/btc-stamps/tx-builder/actions) [![codecov](https://codecov.io/gh/btc-stamps/tx-builder/graph/badge.svg?token=AWB6I9Z0AQ)](https://codecov.io/gh/btc-stamps/tx-builder) [![npm](https://img.shields.io/npm/v/@btc-stamps/tx-builder.svg)](https://www.npmjs.com/package/@btc-stamps/tx-builder) |
| [**stamps_sdk**](https://github.com/stampchain-io/stamps_sdk) | SDK — TypeScript library for building with Bitcoin Stamps |
| [**stampchain-mcp**](https://github.com/stampchain-io/stampchain-mcp) | MCP Server — AI integration via Model Context Protocol |

> See also: [**btc-stamps**](https://github.com/btc-stamps) org for protocol tooling and open-source libraries

### Protocol Specifications

| Standard | Description |
|----------|-------------|
| [**stamps**](https://github.com/stampchain-io/stamps) | Bitcoin Stamps Protocol Definition |
| [**src-721**](https://github.com/stampchain-io/src-721) | SRC-721 — Non-fungible token standard for Stamps |
| [**Glyphs**](https://github.com/stampchain-io/Glyphs) | Fungible token meta-protocol built on Counterparty |

### Documentation & Governance

| Resource | Link |
|----------|------|
| Technical Whitepaper | [bitcoinstamps.xyz/en/whitepaper](https://bitcoinstamps.xyz/en/whitepaper/) · [Source](https://github.com/stampchain-io/btc_stamps/tree/dev/docs/whitepaper) |
| SIP Roadmap & Registry | [bitcoinstamps.xyz/en/protocols/sips](https://bitcoinstamps.xyz/en/protocols/sips) |
| SIP Process (SIP-0000) | [GitHub Issue #686](https://github.com/stampchain-io/btc_stamps/issues/686) |
| API Documentation | [stampchain.io/docs](https://stampchain.io/docs) — OpenAPI/Swagger reference |
| Protocol Documentation | [bitcoinstamps.xyz](https://bitcoinstamps.xyz) — Guides, tutorials, and protocol specs |

### Prominent Users of the Bitcoin Stamps Indexer & API

[KuCoin](https://x.com/kucoincom) · [SuperEx](https://x.com/SuperExet) · [OpenStamp](https://x.com/btcOpenStamp) · [Leather Wallet](https://x.com/LeatherBTC)

---

Built with Bitcoin. Permanent by design.
