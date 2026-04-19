<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║              YOUNESS OUKHADJOU · SOFTWARE ENGINEER           ║
╚══════════════════════════════════════════════════════════════╝
```

**I build backend systems that don't fall over.**  
Founding Engineer · Full-Stack · Open to Senior / Staff roles

[![Email](https://img.shields.io/badge/Email-younessoukhadjouu%40gmail.com-0d1117?style=flat&logo=gmail&logoColor=EA4335&labelColor=161b22)](mailto:younessoukhadjouu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0d1117?style=flat&logo=linkedin&logoColor=0A66C2&labelColor=161b22)](https://linkedin.com/in/younessoukhadjou)
[![GitHub](https://img.shields.io/badge/GitHub-YounessBrunno-0d1117?style=flat&logo=github&logoColor=white&labelColor=161b22)](https://github.com/YounessBrunno)

</div>

---

## About

I'm a software engineer with a strong **backend focus** — I design systems that are easy to scale, test, and reason about. I've worked as a **Founding Engineer**, where I owned architecture decisions end-to-end: monorepo structure, service boundaries, deployment topology, and data modeling.

My work spans **REST API design, background job pipelines, graph-based data modeling, transaction processing, and admin tooling** — always with an emphasis on correctness and long-term maintainability over quick hacks.

When I'm not building backend systems, I integrate the frontend layer too — primarily with **Next.js** and **React** — so I can ship complete, production-ready features without handoff friction.

---

## 💼 Experience

### 🟢 Founding Software Engineer — [Evu](https://evu.com) *(Dec 2025 – Present · Remote, US)*

Early-stage startup. I joined as a founding engineer and shaped the entire technical foundation:

- Restructured a fragmented codebase into a **multi-service monorepo** (NestJS, Next.js, Go), standardizing cross-service development and improving long-term maintainability
- Designed and implemented a **modular monolith architecture** (NestJS + PostgreSQL) with clean service boundaries, balancing velocity with future scalability
- Built a **transaction processing service in Go** with atomic operations, idempotent handling, and persistent state logging for ledger correctness
- Deployed a cost-efficient **multi-container stack on EC2** with Dockerized Nginx as a single reverse proxy entry point routing to internal services
- Built a **Next.js BFF layer** to aggregate data client-side and decouple frontend logic from backend services
- Implemented **server components, caching, and partial prerendering** in the admin dashboard to reduce render latency on critical paths
- Structured engineering workflows using **Jira** during MVP phase, enabling coordinated development across contributors

---

### 🔵 Freelance Software Engineer *(Nov 2024 – Present · Remote)*

Delivered 7+ production full-stack applications — working directly with founders to design backend architectures and ship functional MVPs:

- Built APIs with **Express / NestJS** including authentication, RBAC, and structured service layers
- Developed **Next.js + TypeScript** frontends with typed REST contracts, state management, and third-party integrations
- Integrated **AI APIs** (Hugging Face, Gemini, OpenAI) into backend workflows for automated processing and feature augmentation

---

## 🛠 Technical Stack

| Layer | Technologies |
|---|---|
| **Languages** | TypeScript · JavaScript · Go · SQL |
| **Backend** | Node.js · Express · NestJS · REST APIs · BullMQ |
| **Frontend** | React · Next.js · TailwindCSS · Shadcn/UI · TanStack Query |
| **Databases** | PostgreSQL · Redis · Firebase · Supabase |
| **Infrastructure** | Docker · AWS EC2 · NGINX · Prisma |
| **Tooling** | Git · GitHub · Postman · Jest · Zod · Jira |

---

## 🚀 Selected Projects

> Projects chosen to demonstrate depth across system design, async processing, and full-stack delivery.

---

### [Sentivio — Video Emotion Analyzer](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
*Express · PostgreSQL · BullMQ · Redis · Next.js · TypeScript*

A production-grade emotion intelligence system that ingests video, extracts emotional signals, and generates structured timelines and analytics.

- **Async pipeline** with BullMQ + Redis to offload heavy video processing jobs and maintain fast API response times under load
- **Custom signal processing** — noise-reduction algorithms to smooth raw emotion predictions into stable temporal phases with averaged confidence scores
- **Interactive Next.js dashboard** visualizing emotion timelines, phase breakdowns, and analytical summaries

---

### [Cortex Graph — Knowledge Graph API](https://github.com/YounessBrunno/cortex-graph-api)
*Node.js · Express · PostgreSQL · Zod · Docker*

A REST API that models interconnected notes, tasks, and insights as a traversable knowledge graph — without a graph database.

- Engineered **graph-style relational queries** on PostgreSQL using CTEs and recursive joins for multi-level relationship traversal
- Improved query performance **~30%** via PostgreSQL full-text search (FTS) indexing
- Fully **Dockerized** with environment parity — setup in under 3 minutes
- Typed request/response contracts with **Zod** schema validation, reducing runtime errors at the API boundary

---

### [Velar — Perfume Discovery Platform](https://github.com/YounessBrunno/Velar-Perfume-explorer)
*Next.js · TypeScript · Firebase · Supabase · NextAuth*

Full-stack catalogue platform with 300+ items, admin controls, and optimized media delivery.

- Reduced load time **30%** with TanStack Query caching and data fetching optimizations
- Built an **image upload pipeline** on Supabase Storage cutting upload latency from 6s to under 3s
- Admin dashboard with **sub-250ms write performance** via NextAuth + Firestore

---

### [Vetra — AI Mock Interview Platform](https://github.com/YounessBrunno/Ai-Mock-Interview)
*Next.js · Clerk · Firebase · Zod*

Simulates structured interview sessions with real-time AI feedback, secure authentication, and session management.

---

### [Vanilla Node.js Static Server](https://github.com/YounessBrunno/vanilla-node.js-static-server)
*Node.js core — zero dependencies*

Custom HTTP static file server built from scratch. MIME detection, file streaming, directory listings, and 404 handling — Apache-style, in pure Node.js.

---

### [Vanilla Task Manager REST API](https://github.com/YounessBrunno/vanilla-node.js-task-manager-rest-api)
*Node.js core — zero dependencies*

Full REST API with authentication, RBAC, analytics, and file-based JSON storage — using only `http`, `fs`, `crypto`, `events`, `url`, and `path`. No frameworks.

---

## 📊 GitHub Stats

<div align="center">

![Youness's GitHub Stats](https://github-readme-stats.vercel.app/api?username=YounessBrunno&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffffff&text_color=8b949e&icon_color=58a6ff)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YounessBrunno&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffffff&text_color=8b949e)

![GitHub Streak](https://streak-stats.demolab.com?user=YounessBrunno&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=58a6ff&currStreakLabel=ffffff&sideLabels=8b949e&dates=8b949e)

</div>

---

## 📬 Let's Connect

I'm open to **senior backend**, **full-stack**, or **founding engineer** roles where I can own meaningful technical decisions.

If you're building something ambitious — reach out.

[![Email](https://img.shields.io/badge/younessoukhadjouu%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:younessoukhadjouu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/younessoukhadjou)

---

<div align="center">
<sub>Last updated: 2025 · Open to remote opportunities</sub>
</div>

