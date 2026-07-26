# TD Bank Group (td-bank-group)

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
