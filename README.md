# Nebius

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

Nebius is an AI-focused cloud platform spun out of Yandex, offering NVIDIA GPU virtual machines and clusters (GB300, GB200, B300, B200, H200, H100) connected over InfiniBand, managed Kubernetes and Slurm (Soperator), S3-compatible storage, managed PostgreSQL, container registry, MLflow, JupyterLab, vLLM, and the Token Factory inference platform. Nebius exposes a gRPC control plane API, a Terraform provider, a nebius CLI, and Go and TypeScript SDKs.

**Areas:** Artificial Intelligence · Cloud · Compute · GPU · HPC · Inference · Kubernetes · Machine Learning · Storage

## Nebius on APIs.io

Everything profiled for Nebius is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nebius/](https://apis.io/providers/nebius/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Nebius Compute API](https://apis.io/apis/nebius/compute-api/) — The Nebius Compute API provisions and manages virtual machines and GPU clusters with NVIDIA GPUs and InfiniBand interconnect for ML and AI workloads.…
- [Nebius Managed Kubernetes API](https://apis.io/apis/nebius/kubernetes-api/) — The Managed Kubernetes API provisions Kubernetes clusters with GPU and InfiniBand support for distributed training and inference workloads.
- [Nebius Storage API](https://apis.io/apis/nebius/storage-api/) — The Nebius Storage API exposes AWS S3-compatible object storage for ML/AI datasets and model artifacts.
- [Nebius IAM API](https://apis.io/apis/nebius/iam-api/) — The Nebius Identity and Access Management API controls users, service accounts, projects, and resource-level access policies.
- [Nebius Managed Applications API](https://apis.io/apis/nebius/mk8s-applications-api/) — The Managed Applications API deploys and manages JupyterLab, vLLM, Open WebUI, MLflow, and other ready-made apps on Nebius infrastructure.
- [Nebius Token Factory](https://apis.io/apis/nebius/token-factory/) — Nebius Token Factory is the AI model inference platform offering OpenAI-compatible endpoints for serving open-source LLMs on Nebius GPU infrastructure.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/nebius/](https://apis.io/servers/nebius/nebius/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nebius Domain Security](https://apis.io/security/nebius/nebius-domain-security/)
- [Nebius Vulnerability Disclosure](https://apis.io/security/nebius/nebius-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nebius Plans Pricing](https://apis.io/plans/nebius/nebius-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nebius Rate Limits](https://apis.io/rate-limits/nebius/nebius-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nebius Finops](https://apis.io/finops/nebius/nebius-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://nebius.com)
- [Documentation](https://docs.nebius.com)
- [Pricing](https://nebius.com/prices)
- [Support](https://nebius.com/contact)
- [Blog](https://nebius.com/blog)
- [Terms of service](https://nebius.com/legal/terms-of-service)
- [Privacy policy](https://nebius.com/legal/privacy-policy)
- [GitHub](https://github.com/nebius)

## API Evangelist rating

**Kin Score 24.7** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 6.5 |
| Contract governance | 0.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 28.6 |
| Access clarity | 42.1 |

**Agent readiness 10.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
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
| Operation Distinctiveness | na |

**Regulatory alignment 10.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nebius/](https://apis.io/providers/nebius/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nebius: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nebius/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
