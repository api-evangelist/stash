# Stash

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

Stash is an investing and banking app that enables fractional share investing, automated portfolio building, bank account management with a Stock-Back debit card, custodial accounts for minors, IRA retirement accounts, and financial education content. Stash serves over one million customers with $4.3 billion under management, offering a hybrid DIY and robo-advisor investing experience through subscription plans starting at $3 per month.

**Website:** [https://www.stash.com](https://www.stash.com)
**Status:** [https://status.stash.com](https://status.stash.com)
**Engineering Blog:** [https://medium.com/stash-engineering](https://medium.com/stash-engineering)

## APIs.json

This repository contains an [APIs.json](apis.yml) profile for Stash following the APIs.json 0.19 specification.

## Plans

See [plans/plans.yml](plans/plans.yml) for Stash's subscription pricing:

- **Stash Growth** — $3/month: brokerage, smart portfolio, IRA, banking, Stock-Back card
- **Stash+** — $12/month: all Growth features plus kids portfolios, 3% IRA match, enhanced insurance

## Rate Limits

See [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml). Stash does not publish a public developer API with documented rate limits. Account data access is available through Open Banking aggregators such as Plaid.

## FinOps

See [finops/finops.yml](finops/finops.yml). Stash uses a flat subscription model with no per-trade commissions, no account minimums, and no API consumption fees.

## Maintainer

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
