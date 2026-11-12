# ImageStep

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

ImageStep is built by an independent developer for people who wire image steps into n8n workflows, agents and scripts. It provides powerful image manipulation capabilities such as background removal, upscaling, conversion, and metadata extraction, all accessible via a simple REST API for automation and integration.

**Areas:** API · Automation · AI Ops · Deterministic Ops · SDK · CLI

## ImageStep on APIs.io

Everything profiled for ImageStep is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/imagestep-dev/](https://apis.io/providers/imagestep-dev/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [ImageStep Agent API](https://apis.io/apis/imagestep-dev/imagestep-dev-agent-api/) — The agent contract face. `GET /api/v1/agent-guidelines` is the operating rules as one document — public, no key needed. `POST /api/v1/feedback` reports what…
- [ImageStep AI Models API](https://apis.io/apis/imagestep-dev/imagestep-dev-ai-models-api/) — The models the AI ops run on — what `model` may name on a job or a preset step, with each model's price, its categories and how big an image it is handed
- [ImageStep API Key Management API](https://apis.io/apis/imagestep-dev/imagestep-dev-api-key-management-api/) — API keys are issued, listed and revoked from a signed-in console session: a key cannot manage credentials, because one that could mint more could outlive…
- [ImageStep Asset Management API](https://apis.io/apis/imagestep-dev/imagestep-dev-asset-management-api/) — The images you store. Three ways in — one call with the bytes as the body, the three-step upload for large files and batches, or a public URL this service…
- [ImageStep Job Management API](https://apis.io/apis/imagestep-dev/imagestep-dev-job-management-api/) — Asynchronous work: an op, a saved preset or inline steps over a batch of assets, run as one job with a handle. Price it with a dry run, wait on it in the…
- [ImageStep Ops API](https://apis.io/apis/imagestep-dev/imagestep-dev-ops-api/) — The catalogue of atomic operations: what `POST /api/v1/jobs` accepts in `op`, with each op's parameter contract, its price as data, an example request and…
- [ImageStep Preset Management API](https://apis.io/apis/imagestep-dev/imagestep-dev-preset-management-api/) — Presets: named, versioned lists of steps — atomic ops and processing-registry steps — saved once and run by slug, id or slug@version
- [ImageStep Synchronous images API](https://apis.io/apis/imagestep-dev/imagestep-dev-synchronous-images-api/) — Run a deterministic operation while you wait. Nothing is stored.
- [ImageStep Template Management API](https://apis.io/apis/imagestep-dev/imagestep-dev-template-management-api/) — HTML/CSS render templates for the render_template op: create, version, import/export
- [ImageStep Usage API](https://apis.io/apis/imagestep-dev/imagestep-dev-usage-api/) — What this account spent over a window — credits, jobs, items and synchronous calls — grouped by op, API key or day: the number an agent holds a budget against
- [ImageStep Webhooks API](https://apis.io/apis/imagestep-dev/imagestep-dev-webhooks-api/) — Register URLs to receive job events instead of polling, and read back what was delivered. At most 10 endpoints per account. Every delivery is signed with…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Imagestep Dev Webhooks](https://apis.io/asyncapis/imagestep-dev/imagestep-dev-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [ImageStep Agentic Access](https://apis.io/agentic-access/imagestep-dev/imagestep-dev-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [EndpointRequest](https://apis.io/schemas/imagestep-dev/imagestep-dev-endpoint-request/)
- [FinishUploadRequest](https://apis.io/schemas/imagestep-dev/imagestep-dev-finish-upload-request/)
- [FromUrlRequest](https://apis.io/schemas/imagestep-dev/imagestep-dev-from-url-request/)
- [JobRequest](https://apis.io/schemas/imagestep-dev/imagestep-dev-job-request/)
- [PresetData](https://apis.io/schemas/imagestep-dev/imagestep-dev-preset-data/)
- [TemplateData](https://apis.io/schemas/imagestep-dev/imagestep-dev-template-data/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Imagestep Dev Context](https://apis.io/jsonld/imagestep-dev/imagestep-dev-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [ImageStep API Rules](https://apis.io/rules/imagestep-dev/imagestep-dev-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [ImageStep Authentication](https://apis.io/security/imagestep-dev/imagestep-dev-authentication/)
- [ImageStep Domain Security](https://apis.io/security/imagestep-dev/imagestep-dev-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [ImageStep Plans Pricing](https://apis.io/plans/imagestep-dev/imagestep-dev-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://imagestep.dev/)
- [Documentation](https://imagestep.dev/docs)
- [Getting started](https://imagestep.dev/docs/quickstart)
- [API reference](https://api.imagestep.dev/docs)
- [Pricing](https://imagestep.dev/pricing)
- [Support](https://imagestep.dev/support)
- [Changelog](https://imagestep.dev/docs/changelog)
- [Terms of service](https://imagestep.dev/terms)
- [Privacy policy](https://imagestep.dev/privacy)

## API Evangelist rating

**Kin Score 69.1** — exemplar · rubric 0.27.0 · scored 2026-11-12

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 70.9 |
| Contract governance | 79.1 |
| Operational transparency | 31.6 |
| Developer ergonomics | 75.5 |
| Access clarity | 73.2 |

**Agent readiness 58.3** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/imagestep-dev/](https://apis.io/providers/imagestep-dev/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ImageStep: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/imagestep-dev/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
