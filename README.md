# Desjardins Group (desjardins)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Desjardins Group (Mouvement Desjardins) is the largest cooperative financial group in North America, founded in 1900 in Lévis, Quebec by Alphonse Desjardins. It is a federation of caisses populaires (member-owned credit unions) rather than a share-capital chartered bank, comprising the Fédération des caisses Desjardins du Québec and its subsidiaries, the caisses in Quebec and the Caisse Desjardins Ontario Credit Union, regulated in Quebec by the Autorité des marchés financiers (AMF). It holds roughly CAD $470 billion in assets and serves more than 7.8 million members and clients across Quebec, Ontario and beyond.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/desjardins/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/desjardins/refs/heads/main/apis.yml)

## Open Finance & API Posture

Desjardins does **not** publish a first-party public developer portal or a downloadable OpenAPI/Swagger specification. Portal candidates such as `developer.desjardins.com`, `developers.desjardins.com`, `apis.desjardins.com` and `apianddata.desjardins.com` do not resolve (DNS/connection failures); `api.desjardins.com` resolves via Akamai but returns HTTP 404 and is an internal app backend, not documented developer surface.

Consumer financial-data access to Desjardins accounts is delivered today through **third-party aggregators** — Flinks (a Canadian aggregator), Plaid, Finicity and Tink — using aggregator/screen-scraping connectivity rather than a documented Desjardins API. Open Banking Tracker lists no first-party Desjardins API products.

Canada's **Consumer-Driven Banking** framework (the country's open-banking regime, legislated in Budget 2024 / Budget 2025 and overseen by the Financial Consumer Agency of Canada, FCAC) is legislated but **not yet operational**. The Big Six banks must support Phase 1; as a cooperative outside the Big Six, Desjardins **may opt in** rather than being mandated. No FDX participation and no downloadable spec are documented for Desjardins as of this review. There is no US-style Section 1033 posture — this is the Canadian entity.

## Tags

- Financial Services
- Banking
- Canada
- Credit Union
- Caisse Populaire
- Cooperative
- Consumer-Driven Banking
- Data Aggregation
- Quebec

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public first-party API is documented. This is an identity-only (built-stub) record: consumer data access is aggregator-only, and Desjardins' participation in Canada's coming Consumer-Driven Banking framework is optional and not yet live.

## Common Properties

- [Website](https://www.desjardins.com/)
- [LinkedIn](https://ca.linkedin.com/company/desjardins)
- [Privacy Policy](https://www.desjardins.com/ca/privacy/index.jsp)
- [Security](https://www.desjardins.com/en/security.html)
- [Support](https://www.desjardins.com/en/contact-us.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
