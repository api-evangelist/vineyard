# Vineyard

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

Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyard enables seamless object sharing between computation engines through a metadata-payload separation architecture, supporting Python, C++, Rust, and Go clients. The Vineyard Operator provides Kubernetes-native deployment with CRDs for managing clusters, sidecars, backups, and data operations.

**Areas:** Big Data · CNCF · Cloud-Native · Data Engineering · Distributed Systems · In-Memory Storage · Kubernetes · Machine Learning · Metadata Management · Python · Zero-Copy

## Vineyard on APIs.io

Everything profiled for Vineyard is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vineyard/](https://apis.io/providers/vineyard/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Vineyard Kubernetes Operator](https://apis.io/apis/vineyard/vineyard-kubernetes-operator/) — The Vineyard Kubernetes Operator manages vineyard cluster lifecycle and orchestrates shared objects on Kubernetes. It defines CRDs including Vineyardd,…
- [Vineyard Blobs API](https://apis.io/apis/vineyard/vineyard-blobs-api/) — Low-level blob storage operations
- [Vineyard Connection API](https://apis.io/apis/vineyard/vineyard-connection-api/) — Connect to and disconnect from a vineyard server
- [Vineyard Metadata API](https://apis.io/apis/vineyard/vineyard-metadata-api/) — Inspect and manage object metadata
- [Vineyard Names API](https://apis.io/apis/vineyard/vineyard-names-api/) — Associate human-readable names with object IDs
- [Vineyard Objects API](https://apis.io/apis/vineyard/vineyard-objects-api/) — Store and retrieve in-memory objects
- [Vineyard Persistence API](https://apis.io/apis/vineyard/vineyard-persistence-api/) — Persist objects for cross-instance visibility

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Vineyard Agentic Access](https://apis.io/agentic-access/vineyard/vineyard-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Vineyard Object Metadata](https://apis.io/schemas/vineyard/vineyard-metadata/)
- [Vineyard Object](https://apis.io/schemas/vineyard/vineyard-object/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Vineyard Object Structure](https://apis.io/json-structure/vineyard/vineyard-object-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Vineyard Context](https://apis.io/jsonld/vineyard/vineyard-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Vineyard Vocabulary](https://apis.io/vocabularies/vineyard/vineyard-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Vineyard Connect To Server Example](https://apis.io/examples/vineyard/vineyard-connect-to-server-example/)
- [Vineyard Get By Name Example](https://apis.io/examples/vineyard/vineyard-get-by-name-example/)
- [Vineyard Get Object Example](https://apis.io/examples/vineyard/vineyard-get-object-example/)
- [Vineyard Get Object Metadata Example](https://apis.io/examples/vineyard/vineyard-get-object-metadata-example/)
- [Vineyard Put Name Example](https://apis.io/examples/vineyard/vineyard-put-name-example/)
- [Vineyard Put Object Example](https://apis.io/examples/vineyard/vineyard-put-object-example/)

#### Collections (7)

Postman and Open Collection request collections.

- [Vineyard Python Client Blobs API](https://apis.io/collections/vineyard/open-vineyard-blobs-api/)
- [Vineyard Python Client Blobs Connection API](https://apis.io/collections/vineyard/open-vineyard-connection-api/)
- [Vineyard Python Client Blobs Metadata API](https://apis.io/collections/vineyard/open-vineyard-metadata-api/)
- [Vineyard Python Client Blobs Names API](https://apis.io/collections/vineyard/open-vineyard-names-api/)
- [Vineyard Python Client Blobs Objects API](https://apis.io/collections/vineyard/open-vineyard-objects-api/)
- [Vineyard Python Client Blobs Persistence API](https://apis.io/collections/vineyard/open-vineyard-persistence-api/)
- [Vineyard Python Client API](https://apis.io/collections/vineyard/open-vineyard-python-client/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Vineyard — jsonschema rules](https://apis.io/rules/vineyard/vineyard-jsonschema-spectral-rules/)
- [Vineyard API Rules](https://apis.io/rules/vineyard/vineyard-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Vineyard Domain Security](https://apis.io/security/vineyard/vineyard-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Vineyard Plans Pricing](https://apis.io/plans/vineyard/vineyard-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Vineyard Rate Limits](https://apis.io/rate-limits/vineyard/vineyard-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Vineyard Finops](https://apis.io/finops/vineyard/vineyard-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://v6d.io/)
- [Documentation](https://v6d.io/docs.html)
- [Getting started](https://v6d.io/notes/getting-started.html)

## API Evangelist rating

**Kin Score 28.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 49.5 |
| Contract governance | 27.3 |
| Operational transparency | 13.2 |
| Developer ergonomics | 21.4 |
| Access clarity | 7.9 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
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

**Regulatory alignment 10.0** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vineyard/](https://apis.io/providers/vineyard/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vineyard: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vineyard/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
