# Bikky (bikky)

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

Bikky is a New York-based Customer Data Platform (CDP) built exclusively for large, multi-unit restaurant brands, serving thousands of locations for companies such as Bojangles, MOD Pizza, Dave's Hot Chicken, and Long John Silver's. By integrating with point-of-sale, online ordering, payment, and loyalty systems, Bikky builds a single source of truth on guests, cleaning, standardizing, and de-duplicating data to reveal behavior, frequency, lifetime value, and menu performance across channels. Bikky offers push-button API integrations with leading ordering, loyalty, and marketing providers, plus Snowflake data shares, SFTP, and CSV import for data exchange. It does not appear to publish a public, self-service developer API or documentation; integration and data access are arranged directly with Bikky.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bikky/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Customer Data Platform, Guest Analytics, Integrations, Marketing, Loyalty

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Bikky Integrations
Bikky provides push-button API integrations with leading POS, online ordering, loyalty, and marketing providers, sending data in real time for most POS and ordering sources and nightly for reservations and loyalty. Additional data exchange options include Snowflake data shares, SFTP, and CSV upload. No public API reference, base URL, or authentication documentation is published; integration access is arranged directly with Bikky.

**Human URL:** [https://www.bikky.com/integrations](https://www.bikky.com/integrations)

#### Tags:

 - Integrations, Guest Data

#### Properties

- [Documentation](https://www.bikky.com/integrations)

## Common Properties

- [Website](https://bikky.com/)
- [Documentation](https://www.bikky.com/integrations)
- [Login](https://app.bikky.com)
- [Support](https://www.bikky.com/learn-more)
- [Blog](https://www.bikky.com/blog)
- [LinkedIn](https://www.linkedin.com/company/bikky-inc)

## Features

| Name | Description |
|------|-------------|
| Unified Guest Profiles | Cleans, standardizes, and de-duplicates guest data from across channels into a single source of truth covering behavior, frequency, lifetime value, and menu performance. |
| Push-Button API Integrations | Pre-built connectors to leading POS, online ordering, loyalty, and marketing providers that ingest data in real time for most POS and ordering sources and nightly for reservations and loyalty. |
| Snowflake Data Shares | Direct, secure data sharing for brands that operate their own Snowflake data warehouse, with no copying or movement of data required. |
| SFTP and CSV Data Exchange | Push and pull SFTP integrations plus direct CSV upload for core data types where a push-button integration is not available. |
| Data Assistant | Guided analytics surface for exploring guest behavior, menu performance, and campaign impact without requiring SQL or a data team. |

## Integrations

| Name | Description |
|------|-------------|
| Ordering | Online and digital ordering platforms, including Clover, Olo, and Qu. |
| Point of Sale | Cloud and on-premise POS systems across both modern and legacy providers, sending guest and transaction data in real time. |
| Third Party Delivery | Marketplace and delivery platforms feeding off-premise order data into guest profiles. |
| Catering | First-party catering integrations capturing large-order and B2B guest activity. |
| Payments | Payment processors, including Fiserv, FreedomPay, and Heartland. |
| Loyalty | Loyalty and rewards platforms, including Punchh, Sparkfly, and Thanx, synced nightly. |
| Feedback | Guest feedback and survey platforms, including Ovation and Tattle. |
| Marketing | Marketing and messaging platforms, including Braze, Attentive, and Klaviyo. |
| Reservations | Reservation platforms, including OpenTable, Resy, and Tock, synced nightly. |

## Solutions

| Name | Description |
|------|-------------|
| Multi-Unit Restaurant Brands | Customer data platform purpose-built for large, multi-location restaurant brands such as Bojangles, MOD Pizza, Dave's Hot Chicken, and Long John Silver's, unifying guest data across thousands of locations. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
