# Starling Bank

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

Starling Bank is a UK app-only digital challenger bank founded in 2014 by Anne Boden and headquartered in London, holding a full UK banking licence and authorised and regulated by the Prudential Regulation Authority and the Financial Conduct Authority (FSCS-protected, SWIFT SRLGGB2L). It is a privately held company - not a mutual and not publicly listed - backed by investors including Goldman Sachs, Fidelity, and the Qatar Investment Authority, and it also licenses its core banking platform as Software-as-a-Service under the "Engine by Starling" brand. As an FCA-authorised ASPSP it participates in UK Open Banking / PSD2, but Starling is best known for its own developer-friendly, bespoke RESTful Developer API (accounts, transaction feed, payments, payees, savings goals/spaces, cards, mandates, and identity) served over OAuth2 at api.starlingbank.com with a full sandbox, alongside its Open Banking Read/Write (AIS, PIS, CBPII) conformance to the Open Banking Implementation Entity (OBIE) standard secured with FAPI-grade OAuth2/OIDC, mutual-TLS, and PSD2 strong customer authentication. Starling is a challenger bank and is not one of the nine CMA9 mandated banks.

**Areas:** Financial Services · Banking · Open Banking · PSD2 · OBIE · United Kingdom · Payments · Account Information · Challenger Bank · Fintech · FAPI · Consumer Banking

## Starling Bank on APIs.io

Everything profiled for Starling Bank is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/starling-bank/](https://apis.io/providers/starling-bank/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Starling Accounts API](https://apis.io/apis/starling-bank/starling-accounts-api/) — Bespoke Starling Developer API for retrieving a customer's accounts, account identifiers (sort code / account number), and balances. Served over OAuth2 at…
- [Starling Account Holder API](https://apis.io/apis/starling-bank/starling-account-holder-api/) — Returns account-holder profile information - the type of account holder (individual, business, joint, sole trader), name, and registered details - from the…
- [Starling Transaction Feed API](https://apis.io/apis/starling-bank/starling-transaction-feed-api/) — The Starling transaction feed (feed items) API exposes real-time transaction activity, feed-item detail, spending categories, receipts, and attachments for…
- [Starling Payments API](https://apis.io/apis/starling-bank/starling-payments-api/) — Initiate and manage domestic and scheduled payments, payment orders, and standing orders from a Starling account through the bespoke Developer API, secured…
- [Starling Payees API](https://apis.io/apis/starling-bank/starling-payees-api/) — Create, list, and manage payees (beneficiaries) and payee accounts used when initiating payments from a Starling account via the bespoke Developer API.
- [Starling Savings Goals API](https://apis.io/apis/starling-bank/starling-savings-goals-api/) — Create and manage Savings Goals (Spaces), add or withdraw money, and round-up transfers within a Starling account through the bespoke Developer API.
- [Starling Cards API](https://apis.io/apis/starling-bank/starling-cards-api/) — Retrieve card details and control card settings - enabling or disabling the card and per-feature controls (ATM, online, mobile wallet, magstripe, gambling)…
- [Starling Mandates API](https://apis.io/apis/starling-bank/starling-mandates-api/) — List and cancel direct debit mandates on a Starling account through the bespoke Developer API.
- [Starling Identity API](https://apis.io/apis/starling-bank/starling-identity-api/) — Returns the identity and token/authorising-individual context for the authenticated Starling user, including the scopes granted to the access token, via the…
- [Starling Account and Transaction Information API (AIS, OBIE Read/Write)](https://apis.io/apis/starling-bank/starling-account-transaction-api/) — UK Open Banking Read/Write Account and Transaction Information (AIS) API for accessing account, balance, transaction, and product data as an FCA-authorised…
- [Starling Payment Initiation API (PIS, OBIE Read/Write)](https://apis.io/apis/starling-bank/starling-payment-initiation-api/) — UK Open Banking Read/Write Payment Initiation (PIS) API for initiating domestic and other payments as an FCA-authorised ASPSP, conformant to the OBIE…
- [Starling Confirmation of Funds API (CBPII, OBIE Read/Write)](https://apis.io/apis/starling-bank/starling-confirmation-of-funds-api/) — UK Open Banking Read/Write Confirmation of Funds (CBPII) API allowing a card-based payment instrument issuer to confirm whether funds are available, as an…
- [Starling Bank ATM API](https://apis.io/apis/starling-bank/starling-bank-atm-api/) — Endpoint for getting ATM data
- [Starling Bank BCA API](https://apis.io/apis/starling-bank/starling-bank-bca-api/) — Endpoint for getting Business Current Account data
- [Starling Bank Branch API](https://apis.io/apis/starling-bank/starling-bank-branch-api/) — Endpoint for getting Branch data
- [Starling Bank CCC API](https://apis.io/apis/starling-bank/starling-bank-ccc-api/) — Endpoint for getting Commercial Credit Card data
- [Starling Bank PCA API](https://apis.io/apis/starling-bank/starling-bank-pca-api/) — Endpoint for getting Personal Current Account data
- [Starling Bank SME API](https://apis.io/apis/starling-bank/starling-bank-sme-api/) — Endpoint for getting Unsecured SME Loan data

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Collections (1)

Postman and Open Collection request collections.

- [Open Data API](https://apis.io/collections/starling-bank/open-obie-opendata-swagger/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Starling Bank Opendata Overlay](https://apis.io/overlays/starling-bank/starling-bank-opendata-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Starling Bank Authentication](https://apis.io/security/starling-bank/starling-bank-authentication/)
- [Starling Bank Domain Security](https://apis.io/security/starling-bank/starling-bank-domain-security/)
- [Starling Bank Vulnerability Disclosure](https://apis.io/security/starling-bank/starling-bank-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.starlingbank.com/)
- [Documentation](https://developer.starlingbank.com/docs)
- [Getting started](https://developer.starlingbank.com/docs/getting-started)
- [API reference](https://developer.starlingbank.com/docs)
- [Support](https://developer.starlingbank.com/community)
- [Blog](https://www.starlingbank.com/blog/)
- [Security](https://www.starlingbank.com/security/disclosure/)
- [Compliance](https://www.starlingbank.com/current-account/service-information/api-performance/)
- [Terms of service](https://www.starlingbank.com/legal/)
- [Privacy policy](https://www.starlingbank.com/legal/privacy-notice/)
- [GitHub](https://github.com/starlingbank)
- [Status](https://starlingbank.statuspage.io/)

## API Evangelist rating

**Kin Score 46.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 35.5 |
| Contract governance | 18.2 |
| Operational transparency | 28.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 78.6 |

**Agent readiness 24.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 38.6** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/starling-bank/](https://apis.io/providers/starling-bank/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Starling Bank: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/starling-bank/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
