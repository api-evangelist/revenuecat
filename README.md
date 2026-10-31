# RevenueCat

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

RevenueCat provides in-app subscription and purchase infrastructure for mobile and web apps. It abstracts App Store, Google Play, Amazon, Stripe, Roku, and Paddle billing behind cross-platform SDKs and a REST API, handling receipt validation, entitlements, subscriber state, offerings and paywalls, experiments, and subscription analytics. A v1 REST API manages live subscribers and purchases; a v2 REST API manages the project catalog (projects, apps, products, entitlements, offerings, packages); webhooks stream subscription lifecycle events.

**Areas:** Subscription · In-App Purchases · Billing · Mobile · Entitlements

## RevenueCat on APIs.io

Everything profiled for RevenueCat is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/revenuecat/](https://apis.io/providers/revenuecat/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [RevenueCat Webhooks](https://apis.io/apis/revenuecat/revenuecat-webhooks/) — Outbound webhooks that POST subscription lifecycle events (INITIAL_PURCHASE, RENEWAL, CANCELLATION, EXPIRATION, BILLING_ISSUE, PRODUCT_CHANGE, and more) to…
- [RevenueCat Apps API](https://apis.io/apis/revenuecat/revenuecat-apps-api/) — v2 app (platform integration) management.
- [RevenueCat Customers API](https://apis.io/apis/revenuecat/revenuecat-customers-api/) — v2 customer management.
- [RevenueCat Entitlements (v1) API](https://apis.io/apis/revenuecat/revenuecat-entitlements-v1-api/) — v1 promotional entitlement grant and revoke.
- [RevenueCat Entitlements (v2) API](https://apis.io/apis/revenuecat/revenuecat-entitlements-v2-api/) — v2 entitlement definitions.
- [RevenueCat Offerings (v1) API](https://apis.io/apis/revenuecat/revenuecat-offerings-v1-api/) — v1 offering fetch and override.
- [RevenueCat Offerings (v2) API](https://apis.io/apis/revenuecat/revenuecat-offerings-v2-api/) — v2 offering definitions.
- [RevenueCat Packages API](https://apis.io/apis/revenuecat/revenuecat-packages-api/) — v2 package definitions within an offering.
- [RevenueCat Products API](https://apis.io/apis/revenuecat/revenuecat-products-api/) — v2 product catalog management.
- [RevenueCat Projects API](https://apis.io/apis/revenuecat/revenuecat-projects-api/) — v2 project management.
- [RevenueCat Purchases API](https://apis.io/apis/revenuecat/revenuecat-purchases-api/) — v1 receipt validation and transaction lifecycle operations.
- [RevenueCat Subscribers API](https://apis.io/apis/revenuecat/revenuecat-subscribers-api/) — v1 customer (app user) records, attributes, and state.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Revenuecat Agentic Access](https://apis.io/agentic-access/revenuecat/revenuecat-agentic-access/)

#### Collections (12)

Postman and Open Collection request collections.

- [RevenueCat REST API](https://apis.io/collections/revenuecat/open-revenuecat/)
- [RevenueCat REST Apps API](https://apis.io/collections/revenuecat/open-revenuecat-apps-api/)
- [RevenueCat REST Apps Customers API](https://apis.io/collections/revenuecat/open-revenuecat-customers-api/)
- [RevenueCat REST Apps Entitlements (v1) API](https://apis.io/collections/revenuecat/open-revenuecat-entitlements-v1-api/)
- [RevenueCat REST Apps Entitlements (v2) API](https://apis.io/collections/revenuecat/open-revenuecat-entitlements-v2-api/)
- [RevenueCat REST Apps Offerings (v1) API](https://apis.io/collections/revenuecat/open-revenuecat-offerings-v1-api/)
- [RevenueCat REST Apps Offerings (v2) API](https://apis.io/collections/revenuecat/open-revenuecat-offerings-v2-api/)
- [RevenueCat REST Apps Packages API](https://apis.io/collections/revenuecat/open-revenuecat-packages-api/)
- [RevenueCat REST Apps Products API](https://apis.io/collections/revenuecat/open-revenuecat-products-api/)
- [RevenueCat REST Apps Projects API](https://apis.io/collections/revenuecat/open-revenuecat-projects-api/)
- [RevenueCat REST Apps Purchases API](https://apis.io/collections/revenuecat/open-revenuecat-purchases-api/)
- [RevenueCat REST Apps Subscribers API](https://apis.io/collections/revenuecat/open-revenuecat-subscribers-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Revenuecat Authentication](https://apis.io/security/revenuecat/revenuecat-authentication/)
- [Revenuecat Domain Security](https://apis.io/security/revenuecat/revenuecat-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Revenuecat Plans Pricing](https://apis.io/plans/revenuecat/revenuecat-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Revenuecat Rate Limits](https://apis.io/rate-limits/revenuecat/revenuecat-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Revenuecat Finops](https://apis.io/finops/revenuecat/revenuecat-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.revenuecat.com/)
- [Documentation](https://www.revenuecat.com/docs)
- [Blog](https://www.revenuecat.com/blog/rss.xml)
- [GitHub](https://github.com/RevenueCat)

## API Evangelist rating

**Kin Score 26.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 45.9 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 31.0 |
| Access clarity | 7.9 |

**Agent readiness 22.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/revenuecat/](https://apis.io/providers/revenuecat/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for RevenueCat: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/revenuecat/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
