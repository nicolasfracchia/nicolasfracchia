<!--
  ─────────────────────────────────────────────────────────────
  This file goes in the repo named after your username:
      github.com/nicolasfracchia/nicolasfracchia  →  README.md
  It renders on your profile page automatically.

  PLACEHOLDERS to fill in / decide (search for "TODO"):
    • TODO:PUBLISH     – publish the avatar repo (make it public), then
                         un-comment its project card below
  ─────────────────────────────────────────────────────────────
-->

# 👋 Nicolas Fracchia

### Senior Full-Stack Developer · Production AI & Privacy-First Systems

I design and ship production-grade backends and AI systems — real-time
pipelines, retrieval-augmented LLMs, and **locally / self-hosted inference** —
for teams that want modern AI **without sending sensitive data to the cloud**.
Strong on security, access control, and auditability, with 14+ years across
startups, agencies, and regulated enterprise (energy, insurance, healthcare,
fintech).

📍 Calgary, AB, Canada &nbsp;·&nbsp; 🟢 Open to senior / tech-lead roles (remote or Canada)

---

### 🛠 Tech

**Backend & AI**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-1FD5F9?style=flat-square&logo=livekit&logoColor=black)

**Frontend**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)

**Data & Infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## 🚀 Featured Projects

### 🧭 [AI Suitability Copilot](https://github.com/nicolasfracchia/suitability-copilot)
An AI-native compliance workflow that turns high-volume account-suitability review
from a manual assembly line into an **exception-handling** system. Async
FastAPI service (Celery + Redis) where an LLM proposes a decision, a
**deterministic policy engine has the final say**, and every step is written to
an **immutable audit log**. Includes human-override endpoints and a full
integration test suite.
`FastAPI` · `PostgreSQL` · `Celery` · `Redis` · `Docker` · `LLM guardrails`

### ⚖️ [RTDRS Hearing Assistant](https://github.com/nicolasfracchia/local-assistant-rag)
A **fully on-device** real-time assistant for rehearsing an Alberta tenancy hearing. Transcribes practice sessions in real time with speaker separation, retrieves relevant legislation through hybrid RAG (pgvector + RRF), and streams structured coaching from a local LLM. — **no audio, transcript, or case data ever leaves the machine.**
`faster-whisper` · `pyannote` · `Ollama` · `pgvector` (hybrid RRF) · `WebSockets`

### 🛰 [Emissions Analytics Engine](https://github.com/nicolasfracchia/highwood-engineering-challenge)
<!-- Consider renaming the repo to emissions-analytics-engine and genericizing the README -->
Idempotent batch ingestion of methane-emissions data with **atomic running
totals under concurrency**, backed by Postgres and a React monitoring dashboard.
`NestJS` · `Next.js` · `PostgreSQL` · `TypeScript` · `concurrency control`

<!-- TODO:PUBLISH — un-comment once the repo is public
### 🗣 Self-Hosted Digital Avatar
Real-time + offline text-to-video avatar pipeline (voice cloning + lip-sync)
running on a **single 8GB laptop GPU**, integrated into a LiveKit agent.
`GPT-SoVITS / CosyVoice2` · `MuseTalk` · `LiveKit` · `self-hosted`
-->

---

## 🧩 What I do best

**Backend architecture & APIs** — FastAPI / NestJS, PostgreSQL data modeling and
migrations, API design & versioning, JWT + Keycloak RBAC, async workers.

**Production AI & real-time systems** — RAG pipelines, STT/TTS, LiveKit
audio/video, local & self-hosted inference (Ollama, Whisper, pyannote), and the
latency / synchronization / session-lifecycle work that makes them reliable.

**Security & regulated environments** — SOC 2 / ISO 27001-aligned practices,
RBAC, immutable audit trails, privacy-by-design; prior enterprise work in
insurance, energy, and healthcare under ISO 9001 / IRAM 27001.

**Full-stack delivery & ownership** — Next.js / React frontends, Docker, CI/CD
(GitHub Actions), Linux / Nginx deployment, end-to-end from requirements to
production.

---

## 💼 Experience

**Tech Lead / Backend-Focused Full-Stack Developer** — Y-Swipe (Calgary) · *Jan 2025 – Present*
Primary backend engineer for a production SaaS platform. Own API architecture,
data modeling, and auth (Keycloak RBAC); build real-time and AI-driven features
(LiveKit, STT/TTS pipelines, live conversational avatars); and drive security
strategy aligned with SOC 2 / ISO 27001.
`Python` · `FastAPI` · `PostgreSQL` · `Docker` · `Keycloak` · `LiveKit`

<details>
<summary><b>Earlier roles</b> (2011–2025)</summary>

<br>

**Full-Stack Developer (Contract)** — Communet, Calgary · *Dec 2024 – Mar 2025*
Delivered a full-stack platform end to end: NestJS + Prisma + PostgreSQL APIs,
JWT auth, Next.js frontend, CI/CD on GitHub Actions, Linux/Nginx deployment.

**Full-Stack Developer** — PathwayPro, Calgary · *Sep 2024 – Nov 2024*
React/Next.js UI, a CMS with JWT auth, and hybrid SSR/CSR for SEO and performance.

**Full-Stack Developer (Independent)** — Calgary & Buenos Aires · *2019 – 2023*
End-to-end web, mobile, and API delivery for multiple clients — PWAs, REST APIs,
React Native apps, inventory/logistics systems, and custom CMS platforms.

**Co-founder & Full-Stack Developer** — Proweb Solutions, Buenos Aires · *2018 – 2019*
Defined technical roadmaps, led architecture across web/mobile, shipped apps to
stores, and mentored junior developers.

**Senior Full-Stack Developer** — BDT Global, Buenos Aires · *2014 – 2019*
Enterprise systems for insurance, energy, and healthcare — CMS-driven claims and
reporting platforms — with performance and tooling improvements.

**Intermediate Full-Stack Developer** — DOMO Solutions, Buenos Aires · *2011 – 2014*
CMS platforms and government-integrated systems, SOAP integrations, and legacy
maintenance under regulatory constraints.

</details>

---

## 🎓 Education

**Full-Stack Software Developer Bootcamp (Intensive)** — University of Calgary
(Robo Garden) · *2023 – 2024*

<details>
<summary>Additional coursework</summary>

<br>

React (Hooks, Router, Redux, Next.js) — Udemy ·
Mobile Development with React Native — edX (Harvard) ·
Advanced JavaScript — IT Master Academy ·
PHP OOP — Educación IT ·
Web Development — A.U.B.A

</details>

---

<!-- Card is generated by .github/workflows/metrics.yml and committed to this repo. -->
## 📊 GitHub

![Most used languages](./github-metrics-languages.svg)

---

## 🌐 Languages

**Spanish** — Native &nbsp;·&nbsp; **English** — Advanced

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/nicolasfracchia)

If you're looking for a senior engineer who can own a backend, ship real-time
and AI-driven features, and bring practical AI into security- and
privacy-sensitive environments — let's talk.