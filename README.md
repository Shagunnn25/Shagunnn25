# Shagun Mogha

Backend & AI Systems Engineer — building full-stack systems end to end: Angular/React
frontends, Spring Boot and FastAPI services, JWT-secured REST APIs, and Postgres/pgvector
AI pipelines.

I care about how systems behave once you add concurrency, failure, and scale — not just
whether the demo works. Currently a B.Tech CS (AI & Deep Learning) undergraduate at Mody
University.

## What I've built

**Praxis — AI Mock Interview Platform**
A three-service system (Angular · Spring Boot · FastAPI) for AI-driven mock interviews.
Spring Boot owns state, auth, and business logic; a stateless FastAPI service handles
LLM-backed evaluation; Postgres + pgvector (on Supabase) stores resume embeddings for
resume-aware question generation.

- Resume PDFs are chunked into 384-dim MiniLM embeddings with an IVFFlat cosine index
- Answers are scored on accuracy/depth/communication via strict JSON-schema structured
  outputs at temperature 0
- Evaluation runs asynchronously with retries so question flow never blocks on scoring
- Interview turns stream over SSE with JWT auth; difficulty adapts through a deterministic,
  clamped (1–5) state machine
- Voice mode derives WPM, filler-word rate, and pause metrics from Whisper word-level
  timestamps

**LibManage — Library Management System**
Angular + Spring Boot + SQLite, with JWT auth and route guards. All business rules —
book availability, borrowing eligibility, uniqueness constraints on member email/roll
number (released correctly on member deletion) — are enforced server-side, and issue/
return workflows compute due dates and fines automatically.

## Experience

- **Software Engineering Intern, Capgemini** (Jun–Aug 2026) — built Praxis and LibManage
- **Backend Development Intern, Shrej India** (Jul–Aug 2025) — Spring Boot backend for
  steel utensils import/export operations; REST APIs for product, client, supplier and
  order management; JWT auth with role-based access control via Spring Security

## Leadership

Chairperson, IEEE Computer Society (Mody University) — organizing committee for IEEE Day
and Quiztech.

## Tech stack

**Languages:** Java · Python · C · SQL
**Backend:** Spring Boot · Spring Security · FastAPI · REST APIs · JWT · Hibernate/JPA · Flyway
**Frontend:** Angular · React · JavaScript
**AI/ML:** RAG · embeddings · LLM structured outputs · Scikit-learn · Pandas · NumPy
**Data:** PostgreSQL (pgvector) · MySQL · SQLite
**Infra:** Docker · Kubernetes · Git · Swagger/OpenAPI · S3-compatible storage

## Featured repositories

| Repo | What it demonstrates |
|---|---|
| `praxis` | Multi-service architecture, async AI evaluation, pgvector |
| `libmanage` | Server-enforced business rules, JWT auth |
| `distributed-job-queue` | Queueing, retries, worker scaling |
| `realtime-collab-messaging` | WebSockets, presence, concurrency |
| `rag-document-intelligence` | Chunking, embeddings, retrieval, structured outputs |
| `system-design-lab` | Written system-design solutions with trade-off analysis |

## Reach me

- Email: mogha.shagun@gmail.com
- GitHub: [@Shagunnn25](https://github.com/Shagunnn25)
- LinkedIn: https://www.linkedin.com/in/shagun-mogha-408746289/
