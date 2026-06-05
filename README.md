# Akash Network (akash-network)

Akash Network is a decentralized cloud marketplace for compute - including GPUs - built on a Cosmos-SDK chain settled in AKT. Tenants post deployment manifests (SDL) and providers bid to host them. Developer surface includes the Akash Console REST API with managed wallets and credit-card billing, the Network Data API for indexed chain and provider data, the underlying Cosmos-SDK chain accessible over gRPC / REST / RPC, the Provider API on each provider, an official Akash Blockchain SDK in Go and JavaScript/TypeScript, the Provider Console, and the akash CLI.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/akash-network/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/akash-network/refs/heads/main/apis.yml)

## Tags

- Decentralized Cloud
- GPU
- Compute
- DePIN
- Cosmos
- Crypto
- Marketplace

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Akash Console API

REST API for the managed Akash Console - deploy workloads with a managed wallet and credit-card billing, list and manage deployments, leases, and providers without needing to run a node or hold AKT directly.

- **Human URL:** [https://akash.network/docs/api-documentation/console-api](https://akash.network/docs/api-documentation/console-api)
- **Base URL:** `https://console.akash.network/`

#### Tags

- REST
- Deployments
- Managed

#### Properties

- [Documentation](https://akash.network/docs/api-documentation/console-api)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akash Network Data API

Indexed network data over REST - blocks, transactions, deployments, leases, providers, GPU availability, and marketplace stats. Used for analytics, provider discovery, and dashboards (the API powering Cloudmos / Akash Stats).

- **Human URL:** [https://akash.network/docs/api-documentation/](https://akash.network/docs/api-documentation/)
- **Base URL:** `https://api.cloudmos.io/`

#### Tags

- Indexer
- Analytics
- Marketplace

#### Properties

- [Documentation](https://akash.network/docs/api-documentation/)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akash Chain Node (gRPC / REST / RPC)

Direct access to the Akash Cosmos-SDK chain over gRPC, REST (LCD), and Tendermint RPC. Used to query state, broadcast transactions, and stream events from a self-run or hosted Akash node.

- **Human URL:** [https://akash.network/docs/api-documentation/](https://akash.network/docs/api-documentation/)
- **Base URL:** `https://akash.network/docs/api-documentation/`

#### Tags

- Cosmos SDK
- gRPC
- REST
- RPC

#### Properties

- [Documentation](https://akash.network/docs/api-documentation/)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akash Provider API

HTTP API exposed by each Akash provider for lease management, manifest submission, log and event streaming, shell access, and service status. Used by tenants and tooling once a lease is established.

- **Human URL:** [https://akash.network/docs/providers/](https://akash.network/docs/providers/)
- **Base URL:** `https://github.com/akash-network/provider`

#### Tags

- Provider
- Leases
- Deployments

#### Properties

- [Documentation](https://akash.network/docs/providers/)
- [Repository](https://github.com/akash-network/provider)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akash Blockchain SDK (Go)

Official Go SDK for the Akash chain - typed message types, client helpers for deployments, leases, and providers, AuthZ and fee-grant support, and the building blocks behind the akash CLI.

- **Human URL:** [https://akash.network/docs/api-documentation/sdk](https://akash.network/docs/api-documentation/sdk)
- **Base URL:** `https://github.com/akash-network/node`

#### Tags

- SDK
- Go
- Cosmos SDK

#### Properties

- [Repository](https://github.com/akash-network/node)
- [Documentation](https://akash.network/docs/api-documentation/sdk)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akashjs - Akash SDK (JavaScript / TypeScript)

Official JavaScript / TypeScript SDK for building Akash applications and tooling - SDL parsing, wallet signing, deployment lifecycle, and lease management.

- **Human URL:** [https://akash.network/docs/api-documentation/sdk](https://akash.network/docs/api-documentation/sdk)
- **Base URL:** `https://github.com/akash-network/akashjs`

#### Tags

- SDK
- JavaScript
- TypeScript

#### Properties

- [Repository](https://github.com/akash-network/akashjs)
- [Documentation](https://akash.network/docs/api-documentation/sdk)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akash CLI

Reference command-line tool for the Akash network - keys, accounts, deployments, bids, leases, manifest send, and provider queries. Built on the Go SDK.

- **Human URL:** [https://akash.network/docs/deployments/akash-cli/installation/](https://akash.network/docs/deployments/akash-cli/installation/)
- **Base URL:** `https://github.com/akash-network/node`

#### Tags

- CLI
- Tooling

#### Properties

- [Documentation](https://akash.network/docs/deployments/akash-cli/installation/)
- [Repository](https://github.com/akash-network/node)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Akash Console (Web)

Hosted web console for browsing the marketplace, deploying SDL manifests, and managing leases - with optional managed wallet and credit-card billing.

- **Human URL:** [https://console.akash.network/](https://console.akash.network/)
- **Base URL:** `https://console.akash.network/`

#### Tags

- Console
- Web App

#### Properties

- [Application](https://console.akash.network/)
- [Postman Collection](collections/akash-network.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/akash-network.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://akash.network/)
- [Documentation](https://akash.network/docs/)
- [A P I  Documentation](https://akash.network/docs/api-documentation/)
- [Git Hub](https://github.com/akash-network)
- [Console](https://console.akash.network/)
- [LinkedIn](https://www.linkedin.com/company/akash-network/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
