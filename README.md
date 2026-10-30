# HashiCorp Vault

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

HashiCorp Vault is a secrets management tool that provides secure storage, access control, and distribution of tokens, passwords, certificates, and encryption keys. It provides a unified interface to any secret while providing tight access control and recording a detailed audit log.

**Areas:** DevOps · Encryption · Infrastructure · Secrets Management · Security

## HashiCorp Vault on APIs.io

Everything profiled for HashiCorp Vault is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hashicorp-vault/](https://apis.io/providers/hashicorp-vault/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [HashiCorp Vault Auth - AppRole API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-auth-approle-api/) — AppRole auth method
- [HashiCorp Vault Auth - Token API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-auth-token-api/) — Token auth method
- [HashiCorp Vault Auth - Userpass API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-auth-userpass-api/) — Username/password auth method
- [HashiCorp Vault Identity API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-identity-api/) — Identity secrets engine
- [HashiCorp Vault Leases API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-leases-api/) — Lease management
- [HashiCorp Vault Policy API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-policy-api/) — ACL policy management
- [HashiCorp Vault Secrets - KV v2 API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-secrets-kv-v2-api/) — Key/Value secrets engine version 2
- [HashiCorp Vault Secrets - Transit API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-secrets-transit-api/) — Transit secrets engine (encryption as a service)
- [HashiCorp Vault System API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-system-api/) — System backend operations (init, seal, mounts, auth, audit)
- [Vault HTTP API](https://apis.io/apis/hashicorp-vault/vault-api/) — The complete Vault HTTP API gives full access to all Vault operations via REST. Includes authentication method APIs (AppRole, LDAP, JWT, Kubernetes, AWS,…
- [HashiCorp Vault Policies API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-policies-api/) — Create, read, update, delete, and list ACL policies.
- [HashiCorp Vault Secrets Config API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-secrets-config-api/) — Configure KV v2 engine settings such as max versions and CAS required.
- [HashiCorp Vault Secrets Data API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-secrets-data-api/) — Read, write, patch, and delete secret data versions in the KV v2 engine.
- [HashiCorp Vault Secrets Metadata API](https://apis.io/apis/hashicorp-vault/hashicorp-vault-secrets-metadata-api/) — Manage metadata and version history for KV v2 secrets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hashicorp Vault Agentic Access](https://apis.io/agentic-access/hashicorp-vault/hashicorp-vault-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [SecretDataRequest](https://apis.io/schemas/hashicorp-vault/vault-kv-secret-data-request/)
- [SecretDataResponse](https://apis.io/schemas/hashicorp-vault/vault-kv-secret-data-response/)
- [HealthResponse](https://apis.io/schemas/hashicorp-vault/vault-sys-health-response/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Vault Kv Secret Data Request Structure](https://apis.io/json-structure/hashicorp-vault/vault-kv-secret-data-request-structure/)
- [Vault Sys Health Response Structure](https://apis.io/json-structure/hashicorp-vault/vault-sys-health-response-structure/)

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Vault Kv Context](https://apis.io/jsonld/hashicorp-vault/vault-kv-context/)
- [Vault Sys Context](https://apis.io/jsonld/hashicorp-vault/vault-sys-context/)

#### Examples (2)

Example requests and responses.

- [Vault Kv Secret Data Response Example](https://apis.io/examples/hashicorp-vault/vault-kv-secret-data-response-example/)
- [Vault Sys Health Response Example](https://apis.io/examples/hashicorp-vault/vault-sys-health-response-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [HashiCorp Vault HTTP API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault/)
- [HashiCorp Vault HTTP Auth - AppRole API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-auth-approle-api/)
- [HashiCorp Vault HTTP Auth - AppRole Auth - Token API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-auth-token-api/)
- [HashiCorp Vault HTTP Auth - AppRole Auth - Userpass API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-auth-userpass-api/)
- [HashiCorp Vault HTTP Auth - AppRole Identity API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-identity-api/)
- [HashiCorp Vault HTTP Auth - AppRole Leases API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-leases-api/)
- [HashiCorp Vault HTTP Auth - AppRole Policy API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-policy-api/)
- [HashiCorp Vault HTTP Auth - AppRole Secrets - KV v2 API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-secrets-kv-v2-api/)
- [HashiCorp Vault HTTP Auth - AppRole Secrets - Transit API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-secrets-transit-api/)
- [HashiCorp Vault HTTP Auth - AppRole System API](https://apis.io/collections/hashicorp-vault/open-hashicorp-vault-system-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hashicorp Vault Authentication](https://apis.io/security/hashicorp-vault/hashicorp-vault-authentication/)
- [Hashicorp Vault Domain Security](https://apis.io/security/hashicorp-vault/hashicorp-vault-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hashicorp Vault Plans Pricing](https://apis.io/plans/hashicorp-vault/hashicorp-vault-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hashicorp Vault Rate Limits](https://apis.io/rate-limits/hashicorp-vault/hashicorp-vault-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hashicorp Vault Finops](https://apis.io/finops/hashicorp-vault/hashicorp-vault-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.vaultproject.io/)
- [Documentation](https://developer.hashicorp.com/vault/docs)
- [Getting started](https://developer.hashicorp.com/vault/tutorials)
- [Pricing](https://www.hashicorp.com/products/vault/pricing)
- [Support](https://support.hashicorp.com)
- [Blog](https://www.hashicorp.com/blog)
- [Terms of service](https://www.hashicorp.com/terms-of-service)
- [Privacy policy](https://www.hashicorp.com/privacy)
- [GitHub](https://github.com/hashicorp/vault)
- [Status](https://status.hashicorp.com)

## API Evangelist rating

**Kin Score 42.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 53.6 |
| Contract governance | 0.0 |
| Operational transparency | 42.1 |
| Developer ergonomics | 46.4 |
| Access clarity | 23.7 |

**Agent readiness 29.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hashicorp-vault/](https://apis.io/providers/hashicorp-vault/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HashiCorp Vault: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hashicorp-vault/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
