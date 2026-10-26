# Starling Bank (starling-bank)

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

Starling Bank is a UK app-only digital challenger bank founded in 2014 by Anne Boden, headquartered in London, holding a full UK banking licence and authorised and regulated by the PRA and FCA (FSCS-protected, SWIFT SRLGGB2L). It is a privately held company - not a mutual and not publicly listed - and also licenses its core banking platform as Software-as-a-Service under the "Engine by Starling" brand. As an FCA-authorised ASPSP, Starling participates in UK Open Banking / PSD2, but is best known for its developer-friendly bespoke RESTful Developer API served over OAuth2 at `api.starlingbank.com` with a full sandbox. Starling is a challenger bank and is not one of the nine CMA9 mandated banks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/starling-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/starling-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Payments
- Account Information
- Challenger Bank
- Fintech
- FAPI

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

Starling exposes two distinct public API surfaces: its own bespoke Developer API (the primary, developer-friendly surface) and its UK Open Banking (OBIE) conformance as an FCA-authorised ASPSP.

### Bespoke Starling Developer API

- **Human URL:** [https://developer.starlingbank.com/docs](https://developer.starlingbank.com/docs)
- **Production Base URL:** `https://api.starlingbank.com/api/v2` (confirmed live - returns HTTP 401 without an OAuth2 access token)
- **Sandbox Base URL:** `https://api-sandbox.starlingbank.com/api/v2` (confirmed live - HTTP 401 without a token)
- **Auth:** OAuth2 bearer access tokens (personal access tokens and full OAuth authorization-code flow)

Documented resource groups (grounded in Starling's official JavaScript SDK): Accounts, Account Holder, Transaction Feed (feed items), Payments, Payees, Savings Goals (Spaces), Cards, Mandates (direct debits), and Identity.

### UK Open Banking (OBIE) Read/Write

Starling is an FCA-authorised ASPSP conformant to the Open Banking Implementation Entity (OBIE) Read/Write standard, covering Account & Transaction Information (AIS), Payment Initiation (PIS), and Confirmation of Funds (CBPII), secured with FAPI-grade OAuth2/OIDC, mutual-TLS, and PSD2 strong customer authentication. These endpoints are provisioned to enrolled, certificate-holding TPPs; the base paths listed follow the OBIE standard shape and were not publicly confirmed during this review.

### UK Open Banking Open Data

The OBIE Open Data standard covers public, unauthenticated reference data (personal / business current accounts, and, for banks with a physical estate, ATMs and branches). Starling is app-only with no branch or ATM estate, and no live Open Data endpoint was confirmed for Starling. The harvested spec in `openapi/` is the shared OBIE Open Data standard, not a Starling contract.

## Common Properties

- [Website](https://www.starlingbank.com/)
- [Developer Portal](https://developer.starlingbank.com/)
- [Documentation](https://developer.starlingbank.com/docs)
- [Getting Started](https://developer.starlingbank.com/docs/getting-started)
- [Open Banking](https://developer.starlingbank.com/docs/open-banking)
- [GitHub Organization](https://github.com/starlingbank)
- [LinkedIn](https://www.linkedin.com/company/starling-bank)
- [Blog](https://www.starlingbank.com/blog/)
- [Status Page](https://starlingbank.statuspage.io/)
- [Support / Community](https://developer.starlingbank.com/community)
- [API Performance / Compliance](https://www.starlingbank.com/current-account/service-information/api-performance/)
- [Terms of Service](https://www.starlingbank.com/legal/)
- [Privacy Policy](https://www.starlingbank.com/legal/privacy-notice/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
