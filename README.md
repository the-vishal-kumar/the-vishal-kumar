### Hi, I'm Vishal Kumar

**Associate Director at [CapGrid](https://capgrid.in), running product and engineering in a CPTO capacity** · 10+ years building distributed, multi-tenant SaaS and AI-driven platforms · AWS Certified Solutions Architect - Professional

I own product, platform, infrastructure and AI for a 20-engineer organization, and I still write production code about half my week. I turn business goals into platform architecture, engineering standards and roadmaps, and I treat cost, reliability and security as product concerns.

📍 Gurugram, India · Open to engineering or product leadership roles in the EU, Singapore, the Gulf and beyond · [thevishalkumar.com](https://thevishalkumar.com)

---

### Impact at a glance

- **Quotation turnaround 45 days → 5** with an AI-driven order-ingestion platform; ~90% straight-through acceptance on AI part matching
- **Cloud spend down 86%**, from ~$14K to ~$2K a month. Nobody asked: when $200K of AWS credits ran out, the bill became mine to fix
- **Big Four technology audit passed** as the sole technical owner, a year after the first independent audit failed
- **Platform at scale:** 100K users, 5K-10K requests/sec, 99.9% uptime, sub-200ms API latency
- **Delivery and quality:** sprint predictability 60% → 85%, PR cycle time ~3 days → 1, production defect leakage down 35%

---

### Career

| Years | Role | Highlights |
|---|---|---|
| 2025 - now | **Associate Director of Engineering**, CapGrid | Operating as CPTO: product, platform, infrastructure and AI with 20 engineers (promoted from SDE 3). Engineering standards (CI/CD, release governance, observability), cloud cost down 86%, Big Four tech audit, ERPNext / Frappe from scratch to v16, senior engineers mentored into tech leads |
| 2023 - 2025 | **Software Development Engineer 3**, CapGrid | AI order ingestion (45 → 5 days), multimodal ingestion (images, Excel, messaging), AI part matching (~90% straight-through), event-driven multi-tenant backend on Node.js, Go and AWS, disaster-recovery strategy |
| 2022 - 2023 | **Backend Engineer**, Bondify (Rotterdam, NL) | Moved on a Dutch Highly Skilled Migrant permit. Template.io contract-drafting engine MVP in two quarters, >90% test coverage. Helped secure [€826K of EU (ERDF) funding](https://kvw3.kansenvoorwest.nl/projecten/projecten-kansen-voor-west-iii/global-debt-origination-platform/) for the platform |
| 2021 - 2022 | **Backend Engineer**, Jio News | Led the Go → Node.js (TypeScript) re-architecture in two months, serving ~5M users across 12+ languages at sub-200ms latency. Recognized for technical architecture |
| 2020 - 2021 | **Software Engineer**, The Lightning Group | Multi-tenant, white-label home-moving and real-estate SaaS ([Moveable.uk](https://moveable.uk)) with tenant-isolated data and configuration-driven deployments |
| 2018 - 2020 | **Software Engineer**, Epitome Technologies | [Novagems](https://novage.ms) workforce platform with GPS tracking, geofencing and automated payroll. Scheduling efficiency +70%. Sprint lead |
| 2016 - 2018 | **Junior Software Engineer**, Igniva Infotech | REST APIs and React Native apps for food delivery, healthcare and EdTech. Best Team Project award |

---

### Reference work in public

Clean-room versions of the patterns I lead at work: small, finished and tested. Results are measured where the code can run locally. No employer code or data.

- **[engineering-standards](https://github.com/the-vishal-kumar/engineering-standards)**: the standards kit I'd hand a new team: a reusable CI quality gate, PR/ADR/postmortem templates, release-readiness checklist, on-call and DR runbooks, and how to measure the effect
- **[tech-strategy-onepager](https://github.com/the-vishal-kumar/tech-strategy-onepager)**: a one-page technology strategy template with a worked (fictional) example: architecture, roadmap, risks, cost model and hiring plan
- **[multi-tenant-event-driven-ref](https://github.com/the-vishal-kumar/multi-tenant-event-driven-ref)**: multi-tenant order processing with Postgres row-level security, idempotency keys, a transactional outbox to SQS, a Go worker with retries and a DLQ, end-to-end tracing, Terraform for AWS (validated, not applied), and a load test measured locally
- **[llm-document-ingestion](https://github.com/the-vishal-kumar/llm-document-ingestion)**: purchase orders (email, CSV, Excel, PDF; images with a vision model) to schema-validated JSON, with rules and an LLM, per-field confidence, catalog matching, a human-review queue and a reproducible eval
- **[database-tradeoffs-lab](https://github.com/the-vishal-kumar/database-tradeoffs-lab)**: runnable demos for my database series, starting with a measured matrix of what PostgreSQL's four isolation levels allow across ten anomalies, pinned by tests
- **[latency-debugging-lab](https://github.com/the-vishal-kumar/latency-debugging-lab)**: find the bottleneck, then scale it: five common slowdowns and the signature each leaves in a trace, then what replicas, caching, a connection pooler and rate limits actually buy, measured
- **[systems-data-structures](https://github.com/the-vishal-kumar/systems-data-structures)**: the data structures inside caches, queues and databases, each small enough to read in one sitting and measured on the property that decides whether you'd use it

### Tools I maintain

- **[node22-pnpm-pm2-chromium](https://github.com/the-vishal-kumar/node22-pnpm-pm2-chromium)**: a multi-arch (amd64/arm64) Node 22 base image with pnpm, pm2 and headless Chromium, weekly rebuilt and scanned, with [2K+ pulls on Docker Hub](https://hub.docker.com/r/thevishalkumar/node22-pnpm-pm2-chromium)
- **[claude-local-api](https://github.com/the-vishal-kumar/claude-local-api)**: a dependency-free Go service that exposes the Claude Code CLI as a local HTTP API: localhost-only by default (token required beyond it), isolated per-request workspaces, schema-validated output and generated OpenAPI docs
- **[ev-charging-federated-graphql](https://github.com/the-vishal-kumar/ev-charging-federated-graphql)** (2023): Apollo Federation 2 with change-detecting data ingestion, relay pagination, Docker and tests. Built on Node 18 and Apollo Server 3, both now end-of-life

### Open source

- **[fastify-rate-limit #119](https://github.com/fastify/fastify-rate-limit/pull/119)** (merged): custom rate-limit store example using Sequelize and PostgreSQL
- **[open-kudos (fork)](https://github.com/the-vishal-kumar/open-kudos)**: extended Pagepro's Slack kudos bot with web-based kudos, role-based UI and Slack API updates

### Certifications

- [AWS Certified Solutions Architect - Professional](https://www.credly.com/badges/27547b76-b136-459f-ab2f-a34cbe43301e)
- [AWS Certified Solutions Architect - Associate](https://www.credly.com/badges/5c93bb5e-d403-4077-a199-ca4f2bc55dfb)

### Core stack

- **Architecture:** distributed systems, event-driven microservices, multi-tenant SaaS, LLM-driven automation
- **Languages & APIs:** TypeScript / Node.js (Express, Fastify, Hapi), Go, REST, GraphQL, gRPC, WebSockets
- **Data:** PostgreSQL, MongoDB (Atlas Search, Triggers), DynamoDB, Redis, Elasticsearch, ERPNext / Frappe
- **Cloud & ops:** AWS (EC2, Lambda, SQS, RDS, S3, Route 53, Cognito, CloudWatch), Docker, Nginx, GitHub Actions, observability, DR

---

[![Website](https://img.shields.io/badge/Website-thevishalkumar.com-111111?logo=googlechrome&logoColor=white)](https://thevishalkumar.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-the--vishal--kumar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/the-vishal-kumar/)
[![X](https://img.shields.io/badge/X-@the__vishalkr-000000?logo=x&logoColor=white)](https://x.com/the_vishalkr)
