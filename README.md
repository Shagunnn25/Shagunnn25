<h1 align="center">Hi, I'm Shagun Mogha</h1>
<h3 align="center">Full Stack Developer</h3>

<p align="center">
CS undergrad (AI & Deep Learning) @ Mody University · IEEE Computer Society Chairperson
</p>

```text
$ whoami
> CS undergrad (AI & Deep Learning) @ Mody University
> ex-Software Engineering Intern @ Capgemini
> ex-Backend Development Intern @ Shrej India
> Chairperson, IEEE Computer Society (Mody University)
```

## 💼 Experience

- **Software Engineering Intern, Capgemini** (Jun–Aug 2026) — built Praxis and LibManage
- **Backend Development Intern, Shrej India** (Jul–Aug 2025) — Spring Boot backend for steel utensils import/export operations; REST APIs for product, client, supplier and order management; JWT auth with role-based access control via Spring Security

## ⚙️ Projects

**Praxis — AI Mock Interview Platform**
Three-service system (Angular · Spring Boot · FastAPI) for AI-driven mock interviews. Spring Boot owns state, auth, and business logic; a stateless FastAPI service handles LLM-backed evaluation; Postgres + pgvector (Supabase) stores resume embeddings for resume-aware question generation.
- Resume PDFs chunked into 384-dim MiniLM embeddings with an IVFFlat cosine index
- Answers scored on accuracy/depth/communication via strict JSON-schema structured outputs at temperature 0
- Asynchronous evaluation with retries so question flow never blocks on scoring
- Interview turns stream over SSE with JWT auth; difficulty adapts via a deterministic, clamped (1–5) state machine
- Voice mode derives WPM, filler-word rate, and pause metrics from Whisper word-level timestamps

**LibManage — Library Management System**
Angular + Spring Boot + SQLite, with JWT auth and route guards. All business rules — book availability, borrowing eligibility, uniqueness constraints on member email/roll number — are enforced server-side; issue/return workflows compute due dates and fines automatically.

## 📌 Featured repositories

| Repo | What it demonstrates |
|---|---|
| `praxis` | Multi-service architecture, async AI evaluation, pgvector |
| `libmanage` | Server-enforced business rules, JWT auth |
| `distributed-job-queue` | Queueing, retries, worker scaling |
| `realtime-collab-messaging` | WebSockets, presence, concurrency |
| `rag-document-intelligence` | Chunking, embeddings, retrieval, structured outputs |
| `system-design-lab` | Written system-design solutions with trade-off analysis |

## 🧱 Tech Stack

<p align="left">
<a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<a href="https://www.w3schools.com/c" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/></a>
<a href="https://spring.io/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/></a>
<a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="fastapi" width="40" height="40"/></a>
<a href="https://angular.io" target="_blank" rel="noreferrer"><img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/></a>
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/></a>
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>
<a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" alt="sqlite" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
<a href="https://kubernetes.io" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/></a>
</p>

*RAG · embeddings · LLM structured outputs · Scikit-learn · Pandas · NumPy — applied AI layer on top of the stack above*

## 📡 Contact

<p>
<a href="mailto:mogha.shagun@gmail.com"><img src="https://img.shields.io/badge/Email-black?style=flat-square&logo=gmail" /></a>
<a href="https://github.com/Shagunnn25"><img src="https://img.shields.io/badge/GitHub-black?style=flat-square&logo=github" /></a>
</p>
