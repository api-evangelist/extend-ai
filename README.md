# Extend (extend-ai)

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
