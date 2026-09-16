# Pushpa Raj Adhikari

**Full-stack developer — TypeScript, React / Next.js, Node.js, PostgreSQL**

Sydney, NSW · Full working rights in Australia · Available immediately

[LinkedIn](https://www.linkedin.com/in/pushpa-raj-adhikari) &nbsp;·&nbsp; [pushparajadhikari80@gmail.com](mailto:pushparajadhikari80@gmail.com)

---

## About

Computer Science graduate (University of Texas at Arlington, 2026) who builds web
applications end to end — schema design and API work through to the interface that sits on top
of them.

Recent work has centred on putting language models into products where the output has to be
defensible: scoring against a published rubric, answering only from retrieved source material,
and failing honestly when the model has nothing to go on. I am comfortable owning a feature from
the migration through to the deployed container, and comfortable debugging across that same path
when it breaks.

## Selected projects

### PTE Practice — exam preparation platform
Practice platform covering all 20 PTE Academic task types across Speaking, Writing, Reading and
Listening, scored against each task's rubric and tracked on the 10–90 band.

- Objective tasks scored in code with partial credit; open-ended responses scored by an LLM
  against a per-task rubric, returning a band, a per-criterion breakdown and written feedback.
- Speaking tasks recorded in the browser, transcribed with Whisper, then scored from the
  transcript alongside audio metrics.
- Dashboard reporting predicted overall score, four skills on a shared band, trend over time and
  weakest task types; individual, timed-section and full mock test modes.
- Admin question CRUD with bulk JSON import; local disk storage in development, S3-compatible
  in production.

*Next.js 16 (App Router), TypeScript, Tailwind v4, Prisma, PostgreSQL, NextAuth v5, LLM scoring
API, OpenAI Whisper.* &nbsp;[Repository](https://github.com/pushparajadhikari/PTE-Practice-for-Free)

### Campus Connect — student community platform
Community application for a university cohort: posts with attachments across Lost & Found,
Books, Notes, Events and Study Groups, plus direct and group messaging.

- JWT authentication with bcrypt hashing and role-based access separating student and admin.
- Real-time direct and group chat over Socket.IO.
- Full-text search with category and location filtering; admin moderation dashboard for posts,
  users and reports.
- Integration-tested with Jest and Supertest; single-command deployment via Docker Compose.

*React 18, TypeScript, Vite, Node.js 22, Express 4, PostgreSQL 16, Socket.IO, Docker.*
&nbsp;[Repository](https://github.com/pushparajadhikari/campus-connect)

### StudyAI — Android study assistant
Senior design project at UTA, built by a team of three. **My role: the Android client.**
Students upload lecture PDFs and get answers drawn only from their own material.

- Kotlin and Jetpack Compose (Material 3) client with two nested navigation graphs — an outer
  auth and onboarding host, and an inner five-tab bottom-navigation host.
- A view model scoped to the signed-in graph keeps chat and quiz state alive across tab
  switches.
- OkHttp3 with Gson for multipart upload, and incremental reads of a server-sent-event stream so
  chat responses render as they arrive.

*Kotlin, Jetpack Compose, OkHttp3. Backend (FastAPI, ChromaDB, RAG pipeline) built by teammates.*
&nbsp;[Repository](https://github.com/pushparajadhikari/SeniorDesignProject-AI-Powered-Study-Assistant)

## Technical skills

**Languages** — TypeScript, JavaScript, Python, Kotlin, SQL

**Frontend** — React, Next.js (App Router), Jetpack Compose, Tailwind CSS, Vite

**Backend and data** — Node.js, Express, FastAPI, PostgreSQL, Prisma, SQLite, REST APIs,
Socket.IO, JWT and OAuth authentication

**Infrastructure and tooling** — Docker and Docker Compose, Linux (Ubuntu), Nginx, Git, Jest,
Supertest

**Applied AI** — LLM integration and prompt design, retrieval-augmented generation, speech-to-text
pipelines, rubric-based automated scoring

## Education

**BSc Computer Science** — University of Texas at Arlington, August 2026
