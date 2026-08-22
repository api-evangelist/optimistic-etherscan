# Optimism Etherscan (optimistic-etherscan)

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

Optimism Etherscan is the official blockchain explorer and API platform for the Optimism L2 network (OP Mainnet, chain ID 10). It provides REST APIs for querying Optimism transactions, token events, smart contract source code, account balances, block data, and OP Mainnet statistics. API subscriptions have migrated to Etherscan API V2, enabling a single API key to access Optimism alongside 60+ EVM chains. The free tier covers select chains with 3 calls/second and 100,000 calls/day; paid plans start at $49/month for full multichain access.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/optimistic-etherscan/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/optimistic-etherscan/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Blockchain
- Optimism
- Layer 2
- Ethereum
- EVM
- Web3
- Cryptocurrency

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Optimism Etherscan API

The Optimism Etherscan API provides developer access to OP Mainnet blockchain data via REST endpoints. Modules cover accounts (balances, transaction lists, token transfers), contracts (ABI, source code, verification), transactions (status, receipts, internal txs), blocks (rewards, countdowns, timestamps), tokens (ERC-20/ERC-721 balances, supply, holders), stats (OP supply, gas oracle, network statistics), and a Geth proxy for raw JSON-RPC calls. Use chainid=10 with Etherscan API V2 for unified multichain access.

- **Human URL:** [https://docs.optimism.etherscan.io/](https://docs.optimism.etherscan.io/)
- **Base URL:** `https://api-optimistic.etherscan.io/api`

#### Tags

- Blockchain
- Optimism
- Layer 2
- Ethereum
- EVM
- Transactions
- Smart Contracts
- Token Events

#### Properties

- [Documentation](https://docs.optimism.etherscan.io/)
- [Accounts API](https://docs.optimism.etherscan.io/api-endpoints/accounts)
- [Contracts API](https://docs.optimism.etherscan.io/api-endpoints/contracts)
- [Transactions API](https://docs.optimism.etherscan.io/api-endpoints/stats)
- [Stats API](https://docs.optimism.etherscan.io/api-endpoints/stats-1)
- [Tokens API](https://docs.optimism.etherscan.io/api-endpoints/tokens)
- [Blocks API](https://docs.optimism.etherscan.io/api-endpoints/blocks)
- [Geth Proxy](https://docs.optimism.etherscan.io/api-endpoints/geth-parity-proxy)
- [PRO Endpoints](https://docs.optimism.etherscan.io/api-pro/api-pro-endpoints)
- [Pricing](https://etherscan.io/apis)
- [Sign Up](https://optimistic.etherscan.io/myapikey)
- [Terms of Service](https://etherscan.io/apiterms)
- [Rate Limits](https://docs.optimism.etherscan.io/support/rate-limits)

## Common Properties

- [Portal](https://optimistic.etherscan.io/)
- [Documentation](https://docs.optimism.etherscan.io/)
- [Pricing](https://etherscan.io/apis)
- [Terms of Service](https://etherscan.io/apiterms)
- [Sign Up](https://optimistic.etherscan.io/myapikey)
- [Rate Limits](https://docs.optimism.etherscan.io/support/rate-limits)
- [LLMs.txt](https://docs.etherscan.io/llms.txt)
- [Sandbox / Testnet](https://docs.optimism.etherscan.io/optimism-sepolia-etherscan)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
