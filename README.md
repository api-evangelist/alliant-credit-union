# Alliant Credit Union (alliant-credit-union)

Alliant Credit Union is a federally chartered, member-owned credit union headquartered in Chicago, Illinois, regulated by the National Credit Union Administration (NCUA). Founded in 1935 as the United Airlines Employees' Credit Union and rebranded Alliant in 2003, it is one of the largest credit unions in the United States, with more than 800,000 members and over $19 billion in assets. Alliant operates as a digital-first, branchless institution offering consumer and commercial deposit accounts, high-yield savings and checking, credit cards, auto and home loans, and business banking.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/alliant-credit-union/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alliant-credit-union/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Alliant Credit Union publishes **no public first-party developer API and no developer portal**. Probes of `developer.alliantcreditunion.com` and `api.alliantcreditunion.com` resolve only to Cloudflare wildcard catch-alls (generic 403/404 responses, not an API surface); the primary `alliantcreditunion.com` domain redirects to `alliantcreditunion.org`, which is fully protected by a web application firewall. No public GitHub organization exists.

Consistent with the U.S. open-finance model — which is voluntary and fragmented rather than mandated like the UK/AU regimes — Alliant exposes member financial data only through consumer-permissioned **third-party aggregators** (Plaid, MX, Finicity, Akoya) rather than a directly documented open-banking API. No documented Financial Data Exchange (FDX) participation or published CFPB Section 1033 data-access posture was found at bootstrap time. This is an identity-only provider record; there is no first-party API surface to catalog.

## Tags

- Financial Services
- Banking
- United States
- Credit Union
- Open Finance
- Data Aggregation
- Consumer Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Alliant Credit Union exposes no public first-party developer API. Member data access is available only via third-party aggregators.

## Common Properties

- [Website](https://www.alliantcreditunion.org/)
- [LinkedIn](https://www.linkedin.com/company/alliant-credit-union)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
