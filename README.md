# TD Bank Group (td-bank-group)

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

TD Bank Group (The Toronto-Dominion Bank) is one of Canada's Big Six chartered banks — a federally regulated Schedule I bank headquartered in Toronto and listed on the TSX and NYSE under the ticker TD. It is among North America's largest banks by assets, serving roughly 27 million customers worldwide across Canadian Personal & Commercial Banking (TD Canada Trust), U.S. Retail (TD Bank, N.A. — profiled separately), and Wholesale Banking (TD Securities).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/td-bank-group/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/td-bank-group/refs/heads/main/apis.yml)

## Open-Finance & API Posture

Canada's open-finance regime is **voluntary and not yet operational**. The federal Consumer-Driven Banking framework was legislated in 2024 (Consumer-Driven Banking Act) but implementation is still pending, so there is no mandated first-party data-access API. As a result, the **Canadian TD Bank Group parent publishes no first-party public developer API and no downloadable OpenAPI/Swagger**.

Today, consumer financial-data access is **aggregator-based**: TD Bank Group and Plaid entered into a North American data-access agreement (announced December 2023), letting TD customers connect to Plaid's network of apps more securely. Access is partner-gated (vetted aggregators/fintechs), not self-serve.

Payments run over Canada's shared rails — **Interac e-Transfer** (supported for TD personal and business customers) and **Payments Canada's Real-Time Rail (RTR)**, for which Interac is the exchange solution provider and which supports ISO 20022. TD does not expose a first-party RTR developer API; the RTR sandbox is operated by Payments Canada.

> **Distinct-entity note:** The FDX-aligned, Akoya-based open-banking API suite at `developer.td.com` belongs to the **U.S. subsidiary TD Bank, N.A.** (America's Most Convenient Bank) and is profiled separately under `api-evangelist/td-bank`. It is **not** attributed to this Canadian parent.

## Tags

- Financial Services
- Banking
- Canada
- Big Six
- Schedule I Bank
- Open Banking
- Consumer-Driven Banking
- Interac
- Payments
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs


#### Tags

- Data Aggregation
- Open Banking

#### Properties

- [Documentation](https://stories.td.com/ca/en/news/2023-12-14-td-bank-group-and-plaid-enter-into-north-american-data-acces)

## Common Properties

- [Website](https://www.td.com/ca/en)
- [LinkedIn](https://www.linkedin.com/company/td)
- [Blog](https://stories.td.com/ca/en)
- [Privacy Policy](https://www.td.com/ca/en/privacy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
