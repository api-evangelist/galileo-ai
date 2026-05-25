# Galileo (galileo-ai)

Galileo (galileo.ai, formerly rungalileo.io) is the GenAI evaluation, observability, and production guardrail platform for LLM and agentic applications. The platform provides pre-built and custom evaluators, agentic trace and span logging, dataset and experiment management, prompt management, runtime Protect (guardrails), and integrations with major LLM providers and agent frameworks. Galileo is deployable as SaaS, Virtual Private Cloud (VPC), or on-prem.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/galileo-ai/refs/heads/main/apis.yml)

## Type

- **x-type:** company

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

Public REST API for the Galileo platform (`api.galileo.ai/v2`). Provides projects, datasets, experiments, traces and spans, log streams, prompts, annotations, groups, integrations, users, API keys, and authentication. Auth is via `Galileo-API-Key` header or OAuth2-password bearer token obtained at `/v2/token`.

- **Base URL:** `https://api.galileo.ai`
- **Docs:** https://docs.galileo.ai/
- **API Reference:** https://docs.galileo.ai/api-reference/
- **Canonical OpenAPI:** https://api.galileo.ai/public/v2/openapi.json
- **LLMs.txt index:** https://docs.galileo.ai/llms.txt
- **Local OpenAPI:** [openapi/galileo-ai-openapi.yml](openapi/galileo-ai-openapi.yml)

#### SDKs

- **Python SDK:** [`galileo` on PyPI](https://pypi.org/project/galileo/) ([rungalileo/galileo-python](https://github.com/rungalileo/galileo-python))
- **TypeScript SDK:** [`galileo` on npm](https://www.npmjs.com/package/galileo) ([rungalileo/galileo-js](https://github.com/rungalileo/galileo-js))
- **SDK Examples:** https://github.com/rungalileo/sdk-examples

#### Key Resources

Projects, Datasets, Experiments, Traces, Spans, Log Streams, Prompts, Annotation Templates, Annotation Ratings, Groups, Group Roles, Integrations, API Keys, Users, Auth.

## Features

- 20+ pre-built evaluators (RAG, agents, safety, security)
- Luna models for low-cost LLM-as-judge replacement
- Nested traces and spans (workflow / llm / retriever / tool)
- Experiments against datasets with attached metrics
- Versioned prompt templates
- Annotation templates and SME ratings
- Runtime Protect (guardrails) lifecycle
- Production log streams
- Group-based access control and per-user API keys
- SaaS / VPC / On-prem deployment

## Integrations

OpenAI, LangChain, CrewAI, OpenAI Agents, OpenTelemetry / OpenInference, NVIDIA NeMo Agent Toolkit, MCP.

## Naftiko Capabilities

Capabilities published in `capabilities/`:

- [platform-projects](capabilities/platform-projects.yaml)
- [platform-datasets](capabilities/platform-datasets.yaml)
- [platform-experiments](capabilities/platform-experiments.yaml)
- [platform-annotations](capabilities/platform-annotations.yaml)
- [platform-groups](capabilities/platform-groups.yaml)
- [platform-integrations](capabilities/platform-integrations.yaml)
- [platform-apikeys](capabilities/platform-apikeys.yaml)

## Artifacts

- [OpenAPI](openapi/galileo-ai-openapi.yml)
- [JSON Schema](json-schema/) — project, dataset, experiment, trace, metric
- [JSON Structure](json-structure/galileo-ai-core-structure.json)
- [JSON-LD context](json-ld/galileo-ai-context.jsonld)
- [Vocabulary](vocabulary/galileo-ai-vocabulary.yml)
- [Spectral rules](rules/galileo-ai-rules.yml)
- [Examples](examples/)
- [Plans](plans/galileo-ai-plans-pricing.yml) — Developer (free), Starter, Pro / Enterprise
- [Rate Limits](rate-limits/galileo-ai-rate-limits.yml) — per-key + per-tier monthly quotas
- [FinOps](finops/galileo-ai-finops.yml) — FOCUS-aligned

## Common Properties

- [Website](https://galileo.ai/)
- [Developer Portal](https://docs.galileo.ai/)
- [API Reference](https://docs.galileo.ai/api-reference/)
- [Pricing](https://galileo.ai/pricing)
- [Blog](https://galileo.ai/blog)
- [GitHub Organization](https://github.com/rungalileo)
- [LinkedIn](https://www.linkedin.com/company/galileo-ai)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
