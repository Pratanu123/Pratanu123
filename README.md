# 👋 Hi, I'm Pratanu Khajanchi

Engineering Lead | Polyglot Backend Engineer | Distributed Systems | End-to-End Delivery

Backend engineer with 8+ years of experience building scalable, high-performance systems across InsurTech, PropTech, and EdTech domains. Experienced in leading cross-functional teams, driving architecture decisions, and delivering end-to-end solutions from requirement gathering to production.

Passionate about distributed systems, event-driven architectures, backend performance optimization, and building reliable cloud-native platforms.

---

# 💻 Technical Expertise

## Languages & Frameworks
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-E74430?style=flat&logo=laravel&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

---

## Distributed Systems & Messaging
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

---

## Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)

---

# 🧩 Domains I’ve Worked In

- 🛡️ InsurTech  
- 🏡 PropTech  
- 📚 EdTech  
- ⚙️ Distributed Systems & Microservices  
- 🤖 AI-powered Automation & Voice Workflows  

---

# 🚀 Key Engineering Highlights

- Led engineering teams and delivered multiple large-scale projects including AutoNinja (V1/V2), ANPB, HRMS, and NinjaOne.
- Built event-driven systems using Kafka and AWS SNS/SQS for scalable asynchronous processing.
- Designed CI/CD pipelines using Docker, Jenkins, and GitHub Actions.
- Integrated AI-powered voice bot workflows to automate customer interactions.
- Optimized backend systems, APIs, and database queries for performance and scalability.
- Worked extensively on microservices architecture, distributed systems, and production monitoring.

---

# 📌 Public Projects

## 🔹 AI Lead Scoring System (RAG-based)
🔗 https://github.com/Pratanu123/lead-scoring

Local Docker, production-ready AI lead scoring stack: CRM-style ingestion, async RAG scoring, authenticated API, WebSocket job updates, a minimal web UI, and provisioned Grafana dashboards.

### Description
Ingests leads, queues embed/score jobs asynchronously, and returns live job status over WebSockets. Uses Postgres + pgvector for vector search, Redis for rate limiting and job coordination, and optional remote LLM/embedding providers with a local heuristic fallback. Includes API-key auth, Prometheus metrics, Grafana dashboards, and an OpenSearch log pipeline.

### Tech Stack
- Golang (API + worker)
- TypeScript (web UI)
- PostgreSQL + pgvector
- Redis
- Docker
- Prometheus + Grafana
- OpenSearch

### Highlights
- Async embed/score pipeline with WebSocket status updates
- Vector similarity search with pgvector
- API key auth and Redis rate limits
- Outcome feedback loop for RAG quality
- Full local observability (Prometheus, Grafana, OpenSearch)

---

## 🔹 Ticket Triage RAG
🔗 https://github.com/Pratanu123/ticket-triage-rag

Self-hosted support ticket triage using retrieval-augmented generation, confidence-based human escalation, and full observability — runs entirely locally with no external API keys.

### Description
Retrieves relevant knowledge-base docs from ChromaDB, classifies tickets with a local Ollama model, drafts a reply when confidence is high, and escalates otherwise. Postgres is the source of truth; OpenSearch provides search/audit history; Grafana and Prometheus track latency and auto-resolve vs escalate rates. Includes a React dashboard for creating tickets and reviewing escalations.

### Tech Stack
- Python (FastAPI)
- React
- Ollama (llama3.1 + nomic-embed-text)
- ChromaDB
- PostgreSQL
- OpenSearch
- Prometheus + Grafana
- Docker Compose

### Highlights
- Confidence-gated auto-reply vs human escalation
- Fully local RAG stack (no API keys)
- Audit trail via OpenSearch
- Provisioned Grafana observability
- React UI for triage and override workflows

---

## 🔹 Laravel SaaS Boilerplate
🔗 https://github.com/Pratanu123/laravel-saas-boilerplate

Laravel 13 multi-tenant SaaS API starter with Passport auth, Spatie RBAC, billing boundary, OpenAPI docs, admin UI, and tests.

### Description
A shared-database multi-tenant API on Laravel 13 / PHP 8.3+ with tenant resolution (header, domain, subdomain), role-based access control, a swappable billing gateway (fake default + Stripe stub), Scramble OpenAPI docs, and a small session-based landlord admin console. Runnable under Sail with MySQL and Redis, backed by tests that catch wiring regressions.

### Tech Stack
- PHP 8.3+ / Laravel 13
- Laravel Passport
- Spatie Permission (RBAC)
- MySQL + Redis (Sail)
- Scramble (OpenAPI)
- PHPUnit
- Blade admin UI

### Highlights
- Shared-DB tenancy with `tenant_id` isolation
- Passport personal access tokens
- Platform admin / admin / user RBAC
- Billing gateway boundary (subscribe/cancel)
- OpenAPI UI at `/docs/api`

---

## 🔹 Notification Engine
🔗 https://github.com/Pratanu123/notification-engine

Early-stage public repository for a notification engine — scaffolding in place; implementation and docs are next.

### Description
Placeholder public project intended for a reusable notification delivery service (multi-channel messaging, templating, and reliable dispatch). Currently contains an initial README only; more architecture and code will land here as the project develops.

### Tech Stack
- TBD (repository just initialized)

### Highlights
- Public scaffold for upcoming notification-platform work
- Follow the repo for architecture notes and implementation updates

---

# 📬 Connect With Me

- 💼 LinkedIn: https://www.linkedin.com/in/pratanu-khajanchi-003aa6140/
- 📧 pratanukhajanchi@gmail.com
- 🐙 GitHub: https://github.com/Pratanu123

---

> ⚡ I enjoy building scalable backend systems, designing distributed architectures, and solving complex engineering problems.
