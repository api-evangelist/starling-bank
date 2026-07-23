# Starling Bank (starling-bank)

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
