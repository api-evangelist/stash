# Stash

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
