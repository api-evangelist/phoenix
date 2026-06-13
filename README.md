# Arize Phoenix (phoenix)

Arize Phoenix is an open-source AI observability and evaluation platform built on OpenTelemetry, enabling developers to trace, evaluate, and debug LLM applications in production or locally. Phoenix exposes a REST API for programmatically ingesting spans and traces, managing datasets, running experiments, submitting annotations, and querying evaluation results. The platform supports a wide range of LLM frameworks including LangChain, LlamaIndex, OpenAI, Anthropic, and CrewAI through auto-instrumentation. Phoenix can be self-hosted in a single command or used as a managed cloud service (Arize AX), with authentication via API keys and OAuth2/OIDC for enterprise deployments.

- **APIs.json:** https://raw.githubusercontent.com/api-evangelist/phoenix/refs/heads/main/apis.yml
- **Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=phoenix-api-evangelist&utm_content=repo

## Tags

LLM Observability, AI Evaluation, OpenTelemetry, Tracing, LLMOps, AI Monitoring, Open Source, Prompt Engineering, Datasets, Experiments

## APIs

| Name | Description | Human URL | Base URL |
|------|-------------|-----------|----------|
| Arize Phoenix REST API | REST API for trace ingestion, annotation management, dataset upload/export, experiment management, and project operations. | https://arize.com/docs/phoenix | https://app.phoenix.arize.com |

## Plans, Rate Limits, and FinOps

| Resource | Description |
|----------|-------------|
| [Plans & Pricing](plans/phoenix-plans-pricing.yml) | Open Source (free/self-hosted), AX Free (25k spans/mo), AX Pro ($50/mo, 50k spans), AX Enterprise (custom) |
| [Rate Limits](rate-limits/phoenix-rate-limits.yml) | Monthly span and ingestion limits per plan; bearer token auth; brute-force login protection |
| [FinOps](finops/phoenix-finops.yml) | FOCUS-aligned cost model covering span and ingestion billing dimensions, unit economics, and optimization recommendations |

## Timestamps

| Field | Value |
|-------|-------|
| Created | 2026-06-13 |
| Modified | 2026-06-13 |

## Common

| Type | URL |
|------|-----|
| Website | https://arize.com/phoenix/ |
| Documentation | https://arize.com/docs/phoenix |
| GitHub Org | https://github.com/Arize-ai |
| LinkedIn | https://www.linkedin.com/company/arizeai |
| Blog | https://arize.com/blog/ |
| Pricing | https://arize.com/pricing/ |
| X | https://twitter.com/arizeai |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
