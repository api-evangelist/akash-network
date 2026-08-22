# Akash Network (akash-network)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
