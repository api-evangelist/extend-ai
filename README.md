# Extend (extend-ai)

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

Extend is an intelligent document processing platform that turns documents into high quality, structured data. Its REST API at api.extend.ai exposes parsing, extraction, classification, and splitting processors, durable multi-step workflows, evaluation sets, and batch processing for automating document-heavy operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/extend-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/extend-ai/refs/heads/main/apis.yml)

## Tags

- Document Processing
- Document AI
- Intelligent Document Processing
- OCR
- Extraction
- Classification

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Extend Files API

Upload, list, retrieve, and delete files used as inputs to Extend processors and workflows, with optional PDF conversion and password-protected document support.

- **Human URL:** [https://docs.extend.ai/api-reference/endpoints/file/upload-file](https://docs.extend.ai/api-reference/endpoints/file/upload-file)
- **Base URL:** `https://api.extend.ai`

#### Tags

- Files
- Upload
- Documents

#### Properties

- [Documentation](https://docs.extend.ai/api-quickstart)
- [API Reference](https://docs.extend.ai/api-reference/endpoints/file/upload-file)
- [OpenAPI](openapi/extend-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extend-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extend-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Extend Processors API

Synchronous parse, extract, classify, and split endpoints plus management of reusable extractors, classifiers, and splitters for document understanding.

- **Human URL:** [https://docs.extend.ai/api-reference/endpoints/parse/parse-file](https://docs.extend.ai/api-reference/endpoints/parse/parse-file)
- **Base URL:** `https://api.extend.ai`

#### Tags

- Parse
- Extract
- Classify
- Split

#### Properties

- [Documentation](https://docs.extend.ai/extraction/overview)
- [API Reference](https://docs.extend.ai/api-reference/endpoints/parse/parse-file)
- [OpenAPI](openapi/extend-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extend-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extend-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Extend Processor Runs API

Asynchronous run lifecycle for parse, extract, classify, and split operations, returning run objects you poll or receive via webhooks for production workloads.

- **Human URL:** [https://docs.extend.ai/api-reference/endpoints/parse/create-parse-run](https://docs.extend.ai/api-reference/endpoints/parse/create-parse-run)
- **Base URL:** `https://api.extend.ai`

#### Tags

- Processor Runs
- Async
- Polling

#### Properties

- [API Reference](https://docs.extend.ai/api-reference/endpoints/parse/create-parse-run)
- [OpenAPI](openapi/extend-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extend-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extend-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Extend Workflows API

Create and manage versioned, durable multi-step workflows that chain parsing, splitting, extraction, classification, validation, and routing.

- **Human URL:** [https://docs.extend.ai/api-reference/endpoints/workflow/create-workflow](https://docs.extend.ai/api-reference/endpoints/workflow/create-workflow)
- **Base URL:** `https://api.extend.ai`

#### Tags

- Workflows
- Orchestration
- Durable

#### Properties

- [Documentation](https://docs.extend.ai/workflows/overview)
- [API Reference](https://docs.extend.ai/api-reference/endpoints/workflow/create-workflow)
- [OpenAPI](openapi/extend-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extend-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extend-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Extend Workflow Runs API

Run deployed workflows against files, then poll, update, list, and batch workflow runs with priorities, metadata, secrets, and human-review states.

- **Human URL:** [https://docs.extend.ai/api-reference/endpoints/workflow/create-workflow-run](https://docs.extend.ai/api-reference/endpoints/workflow/create-workflow-run)
- **Base URL:** `https://api.extend.ai`

#### Tags

- Workflow Runs
- Execution
- Webhooks

#### Properties

- [API Reference](https://docs.extend.ai/api-reference/endpoints/workflow/create-workflow-run)
- [OpenAPI](openapi/extend-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extend-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extend-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Extend Evaluations API

Create evaluation sets and items against extractors, classifiers, or splitters, trigger evaluation runs, and track batch runs to measure processor accuracy over time.

- **Human URL:** [https://docs.extend.ai/api-reference/endpoints/evaluation/create-evaluation-set](https://docs.extend.ai/api-reference/endpoints/evaluation/create-evaluation-set)
- **Base URL:** `https://api.extend.ai`

#### Tags

- Evaluations
- Batches
- Quality

#### Properties

- [Documentation](https://docs.extend.ai/evaluation/overview)
- [API Reference](https://docs.extend.ai/api-reference/endpoints/evaluation/create-evaluation-set)
- [OpenAPI](openapi/extend-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/extend-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/extend-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/extend-ai)
- [Website](https://www.extend.ai)
- [Documentation](https://docs.extend.ai)
- [Plans](plans/extend-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/extend-ai-rate-limits.yml)
- [Fin Ops](finops/extend-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
