<h1 align="center">Hi, I'm Shagun </h1>
<p align="center"><i>Backend & AI Systems Engineer — I build the parts users never see:
async pipelines, JWT-secured APIs, and Postgres/pgvector-backed AI services.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-Backend%20Engineering-0A0A0A?style=flat-square&labelColor=black" />
  <img src="https://img.shields.io/badge/also-AI%20Systems-0A0A0A?style=flat-square&labelColor=black" />
  <img src="https://img.shields.io/badge/role-IEEE%20CS%20Chairperson-0A0A0A?style=flat-square&labelColor=black" />
</p>

```text
$ who am i
> CS undergrad (AI & Deep Learning) @ Mody University
> ex-Software Engineer Intern @ Capgemini
> ex-Backend Development Intern @ Shrej India
> I care about how systems behave under concurrency, failure, and scale —
  not just whether the demo works.
```

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

## Featured repositories

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
  <img src="[[https://img.shields.io/badge/LinkedIn-add%20link-black?style=flat-square&logo=linkedin](https://www.linkedin.com/in/shagun-mogha-408746289/)](https://www.linkedin.com/in/shagun-mogha-408746289/)" />
</p>
