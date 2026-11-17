<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img width="100%" src="assets/header-light.svg" alt="Muhammad Shehzad. Software engineer: backend systems, data infrastructure and LLM applications." />
</picture>

<a href="https://www.linkedin.com/in/muhammad-shehzad-aslam"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;<a href="mailto:shehzadaslamoza@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-0F766E?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

<img src="https://skillicons.dev/icons?i=go,ts,py,postgres,redis,rabbitmq,kubernetes,docker,react,nextjs,nestjs,githubactions&theme=dark" width="360" alt="Go, TypeScript, Python, PostgreSQL, Redis, RabbitMQ, Kubernetes, Docker, React, Next.js, NestJS, GitHub Actions" />

</div>

---

## 👨‍💻 About me

Software engineer at **SecurePath**. I built **Morpheus**, an internal console that brings Kubernetes, RabbitMQ, databases, container image scans and Sentry errors into one view of every service across 13 environments. I also work on accounting, billing and release testing for the company's main Go and React platform.

Previously an AI and data engineer at **QLU.ai**, where I built a model-agnostic text-to-SQL engine and moved 200 GB of analytics from Postgres to ClickHouse.

I work daily with Claude Code and other AI coding agents.

---

## 🚀 Featured work

> Most of this is company work, so the code is private.

### Morpheus

An internal console that shows how every service at SecurePath is running, in one place.

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" /> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" /> <img src="https://img.shields.io/badge/Harbor-60B932?style=flat-square&logo=harbor&logoColor=white" alt="Harbor" /> <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry" /> <img src="https://img.shields.io/badge/Google%20Chat-00AC47?style=flat-square&logo=googlechat&logoColor=white" alt="Google Chat" />

- One read-only view of 2 clusters and 13 environments: pods, queues, databases, object storage, image CVEs and errors.
- Alerts in Google Chat the moment a service goes down, so the team hears about it before users do.
- Service catalog and dependency map that show which service reads which queue and where a link is broken.
- Automatic hygiene checks: secrets set inline, images missing from the registry, stale builds, config typos.

### Accounting ledger and billing

The accounting and billing core of SecurePath's main platform.

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square" alt="Playwright" /> <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />

- Double-entry ledger with database-enforced invariants; every money action is reversible and auditable.
- Invoice PDFs and emails, QuickBooks export, trial balance and receivables ageing.
- End-to-end release suites that run against dev and UAT before each production promotion.

### Text-to-SQL engine

Lets people ask a large database questions in plain English. Built at QLU.ai.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square" alt="OpenAI" /> <img src="https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white" alt="Anthropic" /> <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black" alt="ClickHouse" />

- Turns plain-English questions into SQL across multiple tables with 200+ columns, and returns a complete answer within 30 seconds.
- Model-agnostic: the same pipeline runs on GPT-4, Claude Opus or other models, chosen per deployment.
- Dashboards for token usage, query execution time and pipeline latency, which cut LLM cost by 30% and made queries 50% faster.
- Migrated 200 GB of analytical data from PostgreSQL to ClickHouse; queries became 10–100× faster.
- Took a 401M-row (106 GB) table from minutes to seconds with indexes and materialized views.

---

## 💼 Experience

| Company | Role | Location | When |
|:---|:---|:---|:---|
| <img src="https://www.google.com/s2/favicons?domain=securepath.tech&sz=64" width="16" height="16" alt="" />&nbsp; [SecurePath Technologies](https://www.securepath.tech/) | Software Developer 1 | 🇺🇸 Remote, US | Jun 2026 – present |
| <img src="https://www.google.com/s2/favicons?domain=edgefirm.io&sz=64" width="16" height="16" alt="" />&nbsp; [EdgeFirm](https://www.edgefirm.io/) | Software Developer | 🇵🇰 Onsite, Karachi, Pakistan | May – Aug 2026 |
| <img src="https://www.google.com/s2/favicons?domain=qlu.ai&sz=64" width="16" height="16" alt="" />&nbsp; [QLU.ai](https://www.qlu.ai/) | AI & Data Engineer | 🇵🇰 Onsite, Karachi, Pakistan | Jun 2025 – May 2026 |
| <img src="https://www.google.com/s2/favicons?domain=securiti.ai&sz=64" width="16" height="16" alt="" />&nbsp; [Securiti.ai](https://securiti.ai/) | Backend Intern, Data Catalog | 🇵🇰 Onsite, Karachi, Pakistan | Jun – Aug 2024 |


---

## 🛠️ Toolkit

| Area | Tools |
|---|---|
| Languages | Go, TypeScript, Python, SQL |
| Backend | Go Fiber, NestJS, FastAPI, REST, gRPC |
| Data | PostgreSQL, ClickHouse, Redis, RabbitMQ, Qdrant |
| LLMs | OpenAI, Anthropic and Gemini APIs, RAG, structured output |
| Platform | Kubernetes, Docker, GitHub Actions, Sentry, AWS, GCP |
| Testing | Go tests, Vitest, Playwright |

---

<div align="center">

</div>
