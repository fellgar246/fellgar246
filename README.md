# Luis Felipe García

**AI Engineer & Fullstack Developer** · Mexico City (CST — overlaps US time zones)

I build and operate AI systems that survive contact with real users. My focus is the part that decides whether an agent actually works in production: reproducible evaluation, LLM tracing and observability, guardrails, human-in-the-loop review, and cost and latency control.

Backed by 3 years of fullstack engineering in Python, TypeScript and Go — owning features end to end, from scope definition with Product through architecture decisions, implementation and code review — and 5 prior years in data analysis and project management that shape how I frame technical work against business constraints.

[feligarcia.site](https://www.feligarcia.site/) · [LinkedIn](https://www.linkedin.com/in/luis-felipe-garciarom/) · fell.gar20@gmail.com

---

## Selected work

### [OpsPilot AI](https://github.com/fellgar246/project-opspilot-nextjs-fastapi) — incident investigation agent with evaluation gates
Agents that look correct in a demo fail on ambiguous or adversarial input, and without evaluation there is no way to know when a change makes them worse.

A human-in-the-loop agent that investigates incidents, proposes hypotheses and drafts postmortems — gated by a reproducible evaluation suite of 30+ cases covering ambiguous signals, insufficient evidence, undeterminable root cause and prompt injection. Every change is measured against the same gate before it ships, every agent decision is traceable end to end, and approvals stay with a human.

`Python` `FastAPI` `LangGraph` `Langfuse` `Next.js` `Docker` `OpenTelemetry` `Prometheus` `Grafana` `Loki`

### [LegalMove Pro](https://github.com/fellgar246/legalmove-pro) — AI contract amendment review · live public demo
Reviewing a contract amendment against its original is slow, manual and easy to get wrong — but a model's output cannot be trusted as a final legal answer.

An asynchronous pipeline that compares both documents and returns structured changes, risk flags and human-review recommendations, with a queue-based worker and infrastructure defined in Terraform. Designed to route its output to human review rather than replace it, and deployed publicly with a mock mode that keeps the demo reproducible at zero model cost.

`Go` `Next.js` `PostgreSQL` `Azure Container Apps` `Blob Storage` `Service Bus` `Terraform` `OpenAI`

### [FitTrack AI](https://github.com/fellgar246/project-fittrack-ai) — AI recommendations in a deployed cloud-native app
Shipping AI features means running them safely: persisted model output, private user data, and infrastructure that can be rebuilt on demand.

A full-stack application with persisted Azure OpenAI recommendations and direct-to-storage uploads secured by short-lived user-delegation SAS tokens. 100 backend and 319 client tests run in CI, with infrastructure managed through Terraform and OIDC-authenticated deployments.

`Python` `FastAPI` `Flutter` `Azure OpenAI` `Azure Container Apps` `Terraform` `GitHub Actions (OIDC)`

---

## Stack

**AI Engineering** — LangGraph, LangChain, Langfuse, RAG, agent design, human-in-the-loop workflows, LLM evaluation suites, tracing and observability, guardrails, prompt engineering, structured outputs, cost and latency control

**Languages** — Python, TypeScript, Go, SQL

**Backend** — FastAPI, Node.js, REST APIs, event-driven architecture, PostgreSQL, DynamoDB, Redis

**Frontend** — React, Next.js, Vue, Jest, Vitest

**Cloud & Infrastructure** — AWS (Lambda, SQS, DynamoDB), Azure (Container Apps, Blob Storage, Service Bus), Docker, Terraform, GitHub Actions, CI/CD

**Observability** — OpenTelemetry, Prometheus, Grafana, Loki

---

## Currently

Fullstack Developer at **Kunzapp**, building Go services and event-driven AWS workflows, and maintaining a Vue Chrome extension with 1,000+ active users.

Open to AI Engineering roles — remote or Mexico City, US time zones.

Spanish (native) · English (C1)
