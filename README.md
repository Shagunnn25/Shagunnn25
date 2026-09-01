```
┌─────────────────────────────────────────────────────────────────┐
│  ██████╗ ██████╗ ██████╗ ████████╗███████╗ ██████╗ ██╗     ██╗   │
│  ██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝██╔═══██╗██║     ██║   │
│  ██████╔╝██║   ██║██████╔╝   ██║   █████╗  ██║   ██║██║     ██║   │
│  ██╔═══╝ ██║   ██║██╔══██╗   ██║   ██╔══╝  ██║   ██║██║     ██║   │
│  ██║     ╚██████╔╝██║  ██║   ██║   ██║     ╚██████╔╝███████╗██║   │
│  ╚═╝      ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝      ╚═════╝ ╚══════╝╚═╝   │
│                                                                   │
│   GITHUB STRATEGY // SHAGUN MOGHA // BACKEND + AI SYSTEMS ENG.   │
└─────────────────────────────────────────────────────────────────┘
```

# ⚡ GitHub Portfolio Strategy — Shagun Mogha

> `status: draft` · `owner: @Shagunnn25` · `objective: campus SE/Backend placements`

**Target:** Software Engineer / Backend Engineer campus placements
**Source of truth:** Resume (Capgemini + Shrej internships, Praxis, LibManage, Health Guard AI, IEEE Computer Society)
**Ground rule followed throughout:** nothing below claims a skill or result not already on your resume. Every technology proposed for a *new* project is explicitly flagged "recommended to learn/use."

---


`───────────────────────────────────────────────────────────────────`

## 🧭 PART 1 — GitHub Positioning

**1. GitHub profile headline**
`Backend & AI Systems Engineer | Spring Boot · FastAPI · Distributed Systems`

**2. One-line bio**
Backend engineer building production-shaped systems — async pipelines, JWT-secured APIs, and Postgres/pgvector-backed AI services.

**3. 3–5 line professional introduction**
CS undergrad (AI specialization) who builds full-stack systems end to end — Angular/React frontends, Spring Boot and FastAPI services, JWT-secured REST APIs, and Postgres/pgvector AI pipelines. Shipped Praxis, a three-service AI mock-interview platform with SSE streaming and async LLM evaluation, during a Software Engineering internship at Capgemini. Chairperson, IEEE Computer Society at Mody University.

**4. Overall positioning**
Not "AI/ML student with side projects." Positioning is: **backend engineer who happens to build AI-integrated systems**, and who understands the plumbing (auth, async processing, schema design, retries, state machines) rather than just calling an LLM API. Praxis is the proof point — it has real backend engineering (SSE, async queues, deterministic state machines, structured outputs) wrapped around the AI layer, not the other way around.

**5. What a recruiter should understand in 30 seconds**
- She ships multi-service systems, not scripts (Praxis = 3 services + vector DB + queue).
- She's done real backend work in industry (Capgemini, Shrej — REST APIs, JWT/RBAC, Spring Security).
- She understands system design fundamentals (server-side business rule enforcement in LibManage, deterministic difficulty state machine in Praxis).
- She leads (IEEE Computer Society Chairperson) — not just an individual contributor.

---


`───────────────────────────────────────────────────────────────────`

## 📄 PART 2 — Profile README

Paste this into a repo named exactly `Shagunnn25/Shagunnn25` (GitHub special profile repo).

```markdown
<h1 align="center">Hi, I'm Shagun 👋</h1>
<p align="center"><i>Backend & AI Systems Engineer — I build the parts users never see:
async pipelines, JWT-secured APIs, and Postgres/pgvector-backed AI services.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-Backend%20Engineering-0A0A0A?style=flat-square&labelColor=black" />
  <img src="https://img.shields.io/badge/also-AI%20Systems-0A0A0A?style=flat-square&labelColor=black" />
  <img src="https://img.shields.io/badge/role-IEEE%20CS%20Chairperson-0A0A0A?style=flat-square&labelColor=black" />
</p>

```text
$ whoami
> CS undergrad (AI & Deep Learning) @ Mody University
> ex-Software Engineering Intern @ Capgemini
> ex-Backend Development Intern @ Shrej India
> I care about how systems behave under concurrency, failure, and scale —
  not just whether the demo works.
```

## ⚙️ What I've built

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

## 💼 Experience

- **Software Engineering Intern, Capgemini** (Jun–Aug 2026) — built Praxis and LibManage
- **Backend Development Intern, Shrej India** (Jul–Aug 2025) — Spring Boot backend for
  steel utensils import/export operations; REST APIs for product, client, supplier and
  order management; JWT auth with role-based access control via Spring Security

## 🎙️ Leadership

Chairperson, IEEE Computer Society (Mody University) — organizing committee for IEEE Day
and Quiztech.

## 🧱 Tech stack

<p>
  <img src="https://img.shields.io/badge/Java-black?style=flat-square&logo=openjdk" />
  <img src="https://img.shields.io/badge/Python-black?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/C-black?style=flat-square&logo=c" />
  <img src="https://img.shields.io/badge/SQL-black?style=flat-square&logo=postgresql" />
  <br/>
  <img src="https://img.shields.io/badge/Spring%20Boot-black?style=flat-square&logo=springboot" />
  <img src="https://img.shields.io/badge/Spring%20Security-black?style=flat-square&logo=springsecurity" />
  <img src="https://img.shields.io/badge/FastAPI-black?style=flat-square&logo=fastapi" />
  <img src="https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens" />
  <br/>
  <img src="https://img.shields.io/badge/Angular-black?style=flat-square&logo=angular" />
  <img src="https://img.shields.io/badge/React-black?style=flat-square&logo=react" />
  <img src="https://img.shields.io/badge/JavaScript-black?style=flat-square&logo=javascript" />
  <br/>
  <img src="https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-black?style=flat-square&logo=postgresql" />
  <img src="https://img.shields.io/badge/MySQL-black?style=flat-square&logo=mysql" />
  <img src="https://img.shields.io/badge/SQLite-black?style=flat-square&logo=sqlite" />
  <br/>
  <img src="https://img.shields.io/badge/Docker-black?style=flat-square&logo=docker" />
  <img src="https://img.shields.io/badge/Kubernetes-black?style=flat-square&logo=kubernetes" />
  <img src="https://img.shields.io/badge/Swagger%2FOpenAPI-black?style=flat-square&logo=swagger" />
</p>

*(RAG · embeddings · LLM structured outputs · Scikit-learn · Pandas · NumPy — applied AI layer on top of the stack above)*

## 📌 Featured repositories

| Repo | What it demonstrates |
|---|---|
| `praxis` | Multi-service architecture, async AI evaluation, pgvector |
| `libmanage` | Server-enforced business rules, JWT auth |
| `distributed-job-queue` | Queueing, retries, worker scaling |
| `realtime-collab-messaging` | WebSockets, presence, concurrency |
| `rag-document-intelligence` | Chunking, embeddings, retrieval, structured outputs |
| `system-design-lab` | Written system-design solutions with trade-off analysis |

## 📡 Reach me

<p>
  <a href="mailto:mogha.shagun@gmail.com"><img src="https://img.shields.io/badge/Email-black?style=flat-square&logo=gmail" /></a>
  <a href="https://github.com/Shagunnn25"><img src="https://img.shields.io/badge/GitHub-black?style=flat-square&logo=github" /></a>
  <img src="https://img.shields.io/badge/LinkedIn-add%20link-black?style=flat-square&logo=linkedin" />
</p>
```

> Badges render live once pasted into an actual GitHub README (they're just shields.io images) — swap any icon slug that doesn't resolve, GitHub's logo registry changes occasionally.

---


`───────────────────────────────────────────────────────────────────`

## 📌 PART 3 — Repository Strategy (6 Pinned Repos)

### 1. `praxis`
- **One-line:** AI mock-interview platform — three-service architecture with async LLM evaluation over Postgres + pgvector.
- **Why valuable:** Your strongest asset. It's the only project that simultaneously proves backend architecture, async processing, and applied AI engineering.
- **Stack:** Angular, Spring Boot, FastAPI, PostgreSQL + pgvector (Supabase), S3-compatible storage, JWT, SSE.
- **Key features:** resume-aware question generation via embeddings; structured-output scoring at temp 0; async evaluation queue with retries; deterministic difficulty state machine; voice analytics from Whisper timestamps.
- **Architecture:** Angular SPA ↔ Spring Boot (auth/state owner) ↔ FastAPI (stateless AI service) ↔ Postgres/pgvector; SSE channel for streamed turns.
- **Folder structure:** `/frontend` (Angular), `/api` (Spring Boot), `/ai-service` (FastAPI), `/infra` (Docker Compose, migrations).
- **README structure:** Problem → Architecture diagram → How evaluation is decoupled from question flow → Embedding pipeline → Setup → Known limitations.
- **Technically interesting because:** it separates a stateful service of record from a stateless AI worker, and makes scoring latency invisible to the user via async + retries — a real production pattern, not a toy integration.
- **Interview questions it invites:** "Why is FastAPI stateless and Spring Boot stateful?" "How do you keep the evaluation queue from losing work if the worker crashes mid-retry?" "Why IVFFlat over exact nearest-neighbor search?" "How does the difficulty state machine stay deterministic across concurrent sessions?"

### 2. `libmanage`
- **One-line:** Library management system with fully server-enforced business rules.
- **Why valuable:** Shows you don't trust the client — a core backend-engineering instinct recruiters screen for.
- **Stack:** Angular, Spring Boot, SQLite, JWT.
- **Key features:** route guards, issue/return workflow, automatic due-date/fine computation, uniqueness constraints that correctly release on deletion.
- **Architecture:** Angular frontend calling a Spring Boot REST API; SQLite for persistence; JWT-secured endpoints.
- **Folder structure:** `/frontend`, `/backend/{controller,service,repository,entity}`, `/backend/src/test`.
- **README structure:** Problem → Business rules enforced (bulleted, explicit) → Data model → Setup → Tests.
- **Technically interesting because:** the uniqueness-constraint release-on-deletion edge case is a real data-integrity problem, not a CRUD demo.
- **Interview questions it invites:** "Where exactly do you validate borrowing eligibility, and why not on the frontend?" "How do you handle a fine calculation if the due date crosses a timezone boundary?"

### 3. `distributed-job-queue` *(new — see Part 4)*
- **One-line:** A job queue with worker pools, retries, and dead-letter handling, built from primitives rather than a managed service.
- **Why valuable:** Directly extends the async pattern you already used in Praxis, but isolates and deepens it — proves it wasn't incidental.
- **Recommended stack:** Python/Java (recommended to learn/use if new: Redis for the queue backend).
- **Key features:** at-least-once delivery, exponential backoff, dead-letter queue, idempotent job handlers.

### 4. `realtime-collab-messaging` *(new)*
- **One-line:** Real-time messaging system with presence and delivery guarantees.
- **Why valuable:** Covers WebSockets/concurrency — a gap your current resume doesn't touch.
- **Recommended stack:** Spring Boot (WebSocket/STOMP) or FastAPI + WebSockets; Redis pub/sub (recommended to learn/use).

### 5. `rag-document-intelligence` *(new)*
- **One-line:** Document ingestion → chunking → embedding → retrieval → structured-output extraction pipeline.
- **Why valuable:** Generalizes the RAG pattern from Praxis into a standalone, reusable system — shows depth beyond one project.
- **Stack:** FastAPI, PostgreSQL + pgvector (already proven skills), structured outputs.

### 6. `system-design-lab` *(new — see Part 6)*
- **One-line:** Written, diagrammed solutions to classic system-design problems with explicit trade-off analysis.
- **Why valuable:** Campus interviews test system-design *reasoning*, not just code. This repo is the artifact that proves you can reason about scale even where you haven't shipped it.

**Avoid pinning:** Health Guard AI in its current form (OCR + classifier + LLM explanation layer) reads as a generic "AI project" unless rebuilt with visible engineering — see Part 8 for the recommendation on it.

---


`───────────────────────────────────────────────────────────────────`

## 🛠️ PART 4 — New Projects (Detailed Design)

### 1. Distributed Job Queue

**Problem statement:** Build a job queue that accepts tasks, distributes them across workers, guarantees at-least-once execution, and survives worker crashes without losing or duplicating work.

**Architecture:** Producer → Queue (Redis lists/streams *recommended to learn/use*) → Worker pool (horizontally scalable) → Result store (Postgres). A separate scheduler handles retries and a dead-letter queue for jobs that exceed max attempts.

**Components:** API for submitting jobs; queue broker; worker process (pollable, scalable via replicas); retry/backoff scheduler; dead-letter store; status/metrics endpoint.

**Database schema (Postgres, illustrative):**
```sql
jobs(id, payload JSONB, status, attempts, max_attempts, created_at, updated_at, run_after)
job_results(job_id, output JSONB, error TEXT, completed_at)
dead_letters(job_id, payload JSONB, last_error, failed_at)
```

**APIs:** `POST /jobs` (submit), `GET /jobs/{id}` (status), `GET /jobs/{id}/result`, `POST /jobs/{id}/retry`.

**Technology choices:** Spring Boot or FastAPI for the API layer (already known); Redis as the broker (recommended to learn/use — you'd be learning it fresh, mark it as such); Postgres for durable result storage (already known).

**Engineering decisions to document:** at-least-once vs exactly-once semantics and why exactly-once is avoided; idempotency key design so retried jobs don't double-apply side effects; backoff strategy (exponential with jitter).

**Scalability considerations:** horizontal worker scaling; partitioning the queue by job type; backpressure when producers outpace workers.

**Failure scenarios:** worker crashes mid-job (must not lose the job — visibility timeout pattern); broker restart (persistence configuration); poison-pill jobs that always fail (dead-letter after N attempts).

**Security considerations:** payload validation before enqueue; auth on submission endpoint; rate limiting per client.

**Testing strategy:** unit tests for retry/backoff logic; integration test that kills a worker mid-job and asserts the job is re-delivered; load test for throughput under N workers.

**Docker/deployment:** `docker-compose.yml` with API, Redis, Postgres, and N worker replicas.

**Metrics you could actually measure:** jobs/sec throughput, p50/p99 job latency, retry rate, dead-letter rate. *(No fabricated numbers — report only what you measure locally.)*

**Realistic MVP:** single-queue, single-worker-type, in-process retries, no dead-letter UI.
**Advanced version:** multiple queues by priority, dead-letter replay UI, Prometheus metrics export.

---

### 2. Real-Time Collaboration / Messaging System

**Problem statement:** Support real-time message delivery between users with presence indicators and delivery guarantees (sent/delivered/read), without message loss on reconnect.

**Architecture:** WebSocket gateway (Spring Boot WebSocket/STOMP or FastAPI + `websockets`) → Redis pub/sub (recommended to learn/use) for fan-out across server instances → Postgres for message history and read receipts.

**Components:** connection manager (tracks active sockets per user), pub/sub fan-out layer, message persistence, presence tracker, REST endpoints for history/backfill.

**Database schema:**
```sql
conversations(id, created_at)
participants(conversation_id, user_id)
messages(id, conversation_id, sender_id, body, sent_at, delivered_at, read_at)
presence(user_id, status, last_seen)
```

**APIs:** WebSocket channel `/ws/conversations/{id}`; REST `GET /conversations/{id}/messages?before=`; `GET /users/{id}/presence`.

**Technology choices:** Spring Boot (known) for the gateway; Redis pub/sub (recommended to learn/use) so the system isn't limited to one server instance; JWT for socket auth (known, reused from Praxis/LibManage).

**Engineering decisions:** how you reconcile messages sent while a client was disconnected (sequence numbers + backfill on reconnect); how presence is kept accurate without a heartbeat storm.

**Scalability:** multiple gateway instances behind a load balancer, coordinated via Redis pub/sub so a message reaches a recipient regardless of which instance holds their socket.

**Failure scenarios:** gateway instance restarts (client must reconnect and backfill); Redis outage (degrade to same-instance-only delivery, documented as a known limitation).

**Security:** JWT validated on socket upgrade; per-conversation authorization check before delivering history.

**Testing:** integration test simulating disconnect/reconnect and asserting no message loss; multi-instance test verifying cross-instance fan-out.

**Docker/deployment:** two gateway instances + Redis + Postgres in `docker-compose.yml` to actually prove the fan-out works.

**Metrics you could measure:** message delivery latency, reconnect backfill correctness (test-asserted, not benchmarked).

**MVP:** single-instance WebSocket chat with persistence.
**Advanced:** multi-instance fan-out via Redis, read receipts, typing indicators.

---

### 3. AI Document Intelligence / RAG Platform

**Problem statement:** Ingest arbitrary documents, make them queryable via retrieval-augmented generation, and return structured, schema-validated answers rather than free text — generalizing the resume-embedding pipeline you already built in Praxis.

**Architecture:** Ingestion service (parses + chunks documents) → embedding service (already-known pattern from Praxis) → pgvector store (known) → retrieval + LLM structured-output layer (known pattern, reused).

**Components:** document upload/parsing, chunking strategy, embedding generation, vector index, retrieval + reranking, structured-output answer generation, source citation tracking.

**Database schema:**
```sql
documents(id, filename, uploaded_at, status)
chunks(id, document_id, content, embedding VECTOR(384), chunk_index)
queries(id, question, answer JSONB, sources JSONB, created_at)
```

**APIs:** `POST /documents` (upload), `POST /query` (question in, structured JSON answer + cited chunk IDs out).

**Technology choices:** FastAPI + pgvector (both already proven in Praxis — this project shows you can generalize the pattern, not just repeat it); IVFFlat or HNSW indexing (HNSW recommended to learn/use as a comparison point to what you used in Praxis).

**Engineering decisions:** chunking strategy trade-offs (fixed-size vs semantic chunking); why structured JSON-schema output (already your approach in Praxis) beats free-text answers for downstream reliability; how you track and return source citations.

**Scalability:** batching embedding generation; index rebuild strategy as corpus grows.

**Failure scenarios:** malformed documents; embedding service timeout (retry pattern, reused from Praxis's async evaluation).

**Security:** document access control per user/tenant; sanitizing extracted text before prompt injection into the LLM call.

**Testing:** retrieval-quality tests against a small labeled Q&A set you construct yourself; schema-validation tests on every LLM response.

**Docker/deployment:** ingestion + query API + Postgres/pgvector in `docker-compose.yml`.

**Metrics you could measure:** retrieval precision@k against your own labeled set, answer schema-validation pass rate, end-to-end query latency.

**MVP:** single-document-type ingestion, fixed-size chunking, basic retrieval.
**Advanced:** semantic chunking, reranking, multi-document citation.

---

### 4. System Design Lab

See Part 6 for full structure — this is a documentation-first repository (no heavy implementation required), designed to demonstrate system-design reasoning explicitly.

---


`───────────────────────────────────────────────────────────────────`

## 🧩 PART 5 — Reusable README Template

```markdown
# Project Name

## Problem
What real problem this solves, in 2–3 sentences.

## Solution
High-level approach in 2–3 sentences.

## Features
- Feature 1
- Feature 2

## Architecture
Short description of the components and how they talk to each other.

### Architecture Diagram
`[insert diagram — draw.io / excalidraw export as PNG/SVG]`

## Tech Stack
| Layer | Technology |
|---|---|
| Frontend | ... |
| Backend | ... |
| Database | ... |
| Infra | ... |

## API Design
| Method | Endpoint | Description |
|---|---|---|
| POST | /resource | ... |

## Database Design
Schema (SQL or ERD image).

## Key Engineering Decisions
- Decision 1 — why, and what alternative was rejected
- Decision 2 — why

## Security
Auth model, input validation, secrets handling.

## Scalability
What scales today, what the known bottleneck is.

## Failure Handling
What happens when a dependency is down / a request fails mid-flight.

## Testing
What's covered (unit/integration), how to run tests.

## Performance / Benchmarks
Only numbers you actually measured, with the measurement method stated.
If none measured yet: "Not yet benchmarked — planned via `<tool>`."

## Local Setup
```bash
# exact commands
```

## Docker Setup
```bash
docker compose up
```

## Screenshots
`[insert]`

## Demo
`[link if deployed]`

## Future Improvements
- Item 1
- Item 2
```

---


`───────────────────────────────────────────────────────────────────`

## 🗺️ PART 6 — `system-design-lab` Structure

```
system-design-lab/
  README.md                  # index + how to read each write-up
  url-shortener/README.md
  rate-limiter/README.md
  notification-system/README.md
  realtime-chat/README.md
  video-streaming/README.md
  food-delivery/README.md
  distributed-job-queue/README.md
```

Each subfolder's README should cover, in this fixed order (so it reads as a system, not a grab-bag):

1. **Requirements** — functional + non-functional (explicitly state assumed scale, e.g. "10M DAU" — and label it as an assumption)
2. **Capacity estimation** — back-of-envelope QPS, storage, bandwidth math, shown explicitly
3. **API design** — key endpoints
4. **Database design** — schema + choice of SQL vs NoSQL, justified
5. **High-level architecture** — diagram + component responsibilities
6. **Caching strategy** — what's cached, invalidation approach
7. **Queues/async** — where and why
8. **Scaling strategy** — horizontal scaling points, sharding if relevant
9. **Failure handling** — single points of failure and mitigations
10. **Trade-offs** — explicitly state what you optimized for and what you gave up

This repo is deliberately writing-heavy, not code-heavy — it's the artifact that answers "walk me through how you'd design X" in an interview, in your own words, ahead of time.

---


`───────────────────────────────────────────────────────────────────`

## ✅ PART 7 — Repository Quality Checklist

Before making any repo public:

- [ ] README covers problem, architecture, setup, and limitations (use Part 5 template)
- [ ] Architecture diagram included (not just prose)
- [ ] Clean, conventional folder structure for the stack used
- [ ] Meaningful, incremental commit history (not one squashed "final commit")
- [ ] `.gitignore` correct for the stack (no `node_modules`, `target/`, `.env`, `__pycache__`)
- [ ] Environment variables documented in `.env.example`, never committed as real values
- [ ] No secrets, API keys, or credentials anywhere in history (check with a secret scanner before pushing)
- [ ] At least basic tests present, and how to run them documented
- [ ] API documented (Swagger/OpenAPI where applicable — you already use this)
- [ ] Dockerized, with a working `docker-compose up`
- [ ] CI/CD — even a minimal GitHub Actions workflow that runs tests on push
- [ ] Screenshots or a short demo (GIF/video link) in the README
- [ ] "Known limitations" section — showing self-awareness reads as senior, not weak
- [ ] "Future improvements" section

---


`───────────────────────────────────────────────────────────────────`

## 🎯 PART 8 — Recruiter Optimization

**What would immediately impress me (as a recruiter):** Praxis pinned first, with a README that leads with the architecture diagram and explains *why* evaluation is async and stateless — that's the 30-second signal that this isn't a tutorial clone. A `system-design-lab` repo also stands out because almost no campus candidates document design reasoning explicitly.

**What would make the profile look weak:** generic beginner repos left visible (calculators, todo apps, weather apps); a Health Guard AI repo with no architecture or engineering detail — right now, on paper, it reads as "called two APIs and a model," even though the actual work may be deeper than that. Either add real engineering detail (data pipeline, model evaluation methodology, error handling) or don't pin it.

**Repos that should be pinned:** `praxis`, `libmanage`, `distributed-job-queue`, `realtime-collab-messaging`, `rag-document-intelligence`, `system-design-lab`.

**Repos that should NOT be pinned:** anything without a README, anything copied from a tutorial without modification, Health Guard AI in its current documented state (until rebuilt with visible engineering depth).

**What should appear above the fold:** profile README with Praxis front and center, tech stack table, and the internship/leadership summary — a recruiter should not have to scroll to find your strongest project.

**Technologies to emphasize:** Spring Boot, FastAPI, PostgreSQL/pgvector, JWT/Spring Security, async processing, system design — these map directly to backend-engineer job descriptions.

**What to de-emphasize:** don't lead with "AI/ML" — lead with backend engineering and let the AI work support that story, not replace it.

**Likely interview questions:** "Walk me through Praxis's architecture." "Why three services instead of one?" "How do you guarantee the evaluation queue doesn't lose a submission?" "What would break first if this had 10,000 concurrent users?" "Why pgvector instead of a dedicated vector DB?"

---


`───────────────────────────────────────────────────────────────────`

## 🚀 PART 9 — Final Deliverable

**1. Final GitHub bio**
Backend engineer building production-shaped systems — async pipelines, JWT-secured APIs, and Postgres/pgvector-backed AI services.

**2. Final complete profile README**
See Part 2 (ready to paste as-is).

**3. Final 6 pinned repositories**
`praxis` · `libmanage` · `distributed-job-queue` · `realtime-collab-messaging` · `rag-document-intelligence` · `system-design-lab`

**4. Final recommended tech stack (as shown on profile)**
Java, Python, SQL · Spring Boot, Spring Security, FastAPI, JWT · Angular, React · PostgreSQL/pgvector, MySQL, SQLite · Docker, Kubernetes · Redis *(recommended to learn/use — not yet on resume)*

**5. Project roadmap, in build order**
1. Polish `praxis` and `libmanage` READMEs to the Part 5 template (no new code needed — highest leverage, lowest effort)
2. `system-design-lab` (writing-heavy, fastest to produce, immediate interview value)
3. `distributed-job-queue` (deepens the async pattern already proven in Praxis)
4. `rag-document-intelligence` (generalizes your strongest existing skill — lowest new-tech risk)
5. `realtime-collab-messaging` (fills the concurrency/WebSockets gap — highest new-tech load, do last)

**6. 30-day execution plan**
- Week 1: Rewrite `praxis` and `libmanage` READMEs + diagrams to Part 5 template; write and publish the profile README (Part 2); pin repos.
- Week 2: Build `system-design-lab` — write up URL Shortener, Rate Limiter, Notification System (3 of 7).
- Week 3: Finish remaining 4 `system-design-lab` write-ups; start `distributed-job-queue` MVP (single queue, single worker type).
- Week 4: Finish `distributed-job-queue` MVP, Dockerize it, add tests and CI.

**7. 60-day execution plan**
- Days 31–40: Build `rag-document-intelligence` MVP (single document type, fixed chunking, basic retrieval).
- Days 41–50: Add citation tracking + a small labeled Q&A test set to `rag-document-intelligence`; write its README.
- Days 51–58: Build `realtime-collab-messaging` MVP (single-instance WebSocket chat + persistence).
- Days 59–60: Run the Part 7 checklist against all 6 pinned repos; fix gaps; final profile review.

**8. Recruiter-ready checklist**
- [ ] Profile README published and pinned repos set
- [ ] All 6 pinned repos pass the Part 7 checklist
- [ ] Every pinned repo has an architecture diagram, not just text
- [ ] No beginner/tutorial repos visible on the profile
- [ ] Health Guard AI either upgraded with real engineering detail or left unpinned
- [ ] LinkedIn/portfolio links added to the profile README placeholders
