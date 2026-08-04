# Galileo (galileo-ai)

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

Galileo (galileo.ai, formerly rungalileo.io) is the GenAI evaluation, observability, and production guardrail platform for LLM and agentic applications. Galileo provides pre-built and custom evaluators, agentic trace and span logging, dataset and experiment management, prompt management, runtime protect (guardrails), and integrations with major LLM providers and agent frameworks. The platform exposes a public REST API plus official Python and TypeScript SDKs and integrates with LangChain, CrewAI, OpenAI Agents, and OpenTelemetry/OpenInference. Galileo is deployable as SaaS, VPC, or on-prem.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/galileo-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/galileo-ai/refs/heads/main/apis.yml)

## Tags

- AI Evaluation
- AI Observability
- GenAI
- Guardrails
- Agentic AI
- LLM
- Tracing
- Experiments
- Prompts
- Datasets

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-25

## APIs

### Galileo Public API

Public REST API for the Galileo platform (api.galileo.ai/v2). Provides projects, datasets, experiments, traces and spans, log streams, prompts, annotations, groups, integrations, users, API keys, and authentication. Authentication is via a Galileo-API-Key header or via OAuth2-password bearer token obtained at /v2/token. The canonical OpenAPI is published at https://api.galileo.ai/public/v2/openapi.json and a documentation index is available at https://docs.galileo.ai/llms.txt.

- **Human URL:** [https://docs.galileo.ai/](https://docs.galileo.ai/)
- **Base URL:** `https://api.galileo.ai`

#### Tags

- Projects
- Datasets
- Experiments
- Traces
- Spans
- LogStreams
- Prompts
- Annotations
- Groups
- Integrations
- ApiKeys
- Users
- Auth

#### Properties

- [Documentation](https://docs.galileo.ai/)
- [API Reference](https://docs.galileo.ai/api-reference/)
- [OpenAPI](openapi/galileo-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/galileo-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/galileo-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Canonical Open A P I](https://api.galileo.ai/public/v2/openapi.json)
- [L L Ms Txt](https://docs.galileo.ai/llms.txt)
- [Getting Started](https://docs.galileo.ai/getting-started/quickstart)
- [Quickstart](https://docs.galileo.ai/getting-started/quickstart)
- [Python S D K](https://pypi.org/project/galileo/)
- [Python S D K Repo](https://github.com/rungalileo/galileo-python)
- [Python S D K Reference](https://docs.galileo.ai/sdk-api/python/sdk-reference)
- [Type Script S D K](https://www.npmjs.com/package/galileo)
- [Type Script S D K Repo](https://github.com/rungalileo/galileo-js)
- [Type Script S D K Reference](https://docs.galileo.ai/sdk-api/typescript/sdk-reference)
- [Authentication](https://docs.galileo.ai/api-reference/auth/)
- [Concepts](https://docs.galileo.ai/concepts/)
- [Metrics](https://docs.galileo.ai/concepts/metrics/overview)
- [Logging](https://docs.galileo.ai/concepts/logging/overview)
- [Protect](https://docs.galileo.ai/concepts/protect/overview)
- [Samples Repo](https://github.com/rungalileo/sdk-examples)
- [Vocabulary](vocabulary/galileo-ai-vocabulary.yml)
- [J S O N L D Context](json-ld/galileo-ai-context.jsonld)
- [Spectral Rules](rules/galileo-ai-rules.yml)

## Common Properties

- [Website](https://galileo.ai/)
- [Developer Portal](https://docs.galileo.ai/)
- [Documentation](https://docs.galileo.ai/)
- [API Reference](https://docs.galileo.ai/api-reference/)
- [Pricing](https://galileo.ai/pricing)
- [Blog](https://galileo.ai/blog)
- [GitHub Organization](https://github.com/rungalileo)
- [LinkedIn](https://www.linkedin.com/company/galileo-ai)
- [Plans](plans/galileo-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/galileo-ai-rate-limits.yml)
- [Fin Ops](finops/galileo-ai-finops.yml)
- [JSON-LD](json-ld/galileo-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/galileo-ai-vocabulary.yml)
- [Spectral Rules](rules/galileo-ai-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
