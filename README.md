```
                                  ██╗   ██╗ ██████╗ ██╗   ██╗███╗   ██╗███████╗███████╗███████╗
                                  ╚██╗ ██╔╝██╔═══██╗██║   ██║████╗  ██║██╔════╝██╔════╝██╔════╝
                                   ╚████╔╝ ██║   ██║██║   ██║██╔██╗ ██║█████╗  ███████╗███████╗
                                    ╚██╔╝  ██║   ██║██║   ██║██║╚██╗██║██╔══╝  ╚════██║╚════██║
                                     ██║   ╚██████╔╝╚██████╔╝██║ ╚████║███████╗███████║███████║
                                     ╚═╝    ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝╚══════╝╚══════╝╚══════╝
```

<div align="center">

**Software Engineer · Fullstack · TypeScript · Go · Node.js · PostgreSQL**

[![Email](https://img.shields.io/badge/-younessoukhadjouu@gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=161b22)](mailto:younessoukhadjouu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=161b22)](https://linkedin.com/in/younessoukhadjou)
[![GitHub](https://img.shields.io/badge/-YounessBrunno-0d1117?style=flat-square&logo=github&logoColor=white&labelColor=161b22)](https://github.com/YounessBrunno)

</div>

---

## About

Backend-first engineer. I design systems that are correct, scalable, and easy to evolve — REST APIs, async job pipelines, transaction processing, modular monolith architecture.

I've owned full technical decisions as a **Founding Engineer**: monorepo structure, service boundaries, data modeling, and deployment topology on EC2. When needed, I ship the frontend too — primarily Next.js and React — so features land without handoff friction.

---

## 💼 Experience

### Evu &nbsp;—&nbsp; Founding Software Engineer
`Dec 2025 – Present` &nbsp;·&nbsp; Remote, United States

> Early-stage startup. Joined as founding engineer and shaped the entire technical foundation from day one.

- Restructured a fragmented codebase into a **multi-service monorepo** (NestJS · Next.js · Go), standardizing cross-service development and improving long-term maintainability
- Designed and implemented a **modular monolith architecture** (NestJS + PostgreSQL) with clean service boundaries — balancing MVP velocity with future scaling
- Built a **transaction processing service in Go** with atomic operations, idempotent handling, and persistent state logging for full ledger correctness
- Deployed a cost-efficient **multi-container stack on EC2** — Dockerized Nginx as a single reverse proxy routing to internal services; local setup under 9 minutes
- Implemented a **Next.js BFF layer** to aggregate client data and isolate frontend logic from backend services
- Built the **admin dashboard** with server components, caching, and partial prerendering to minimize render latency on critical paths
- Structured engineering workflows with **Jira** for coordinated multi-contributor development during MVP phase

---

### Freelance &nbsp;—&nbsp; Software Engineer
`Nov 2024 – Present` &nbsp;·&nbsp; Remote

- Delivered **7+ full-stack applications** (Next.js + Node.js) — backend architecture, frontend, and third-party integrations handled end-to-end
- Built APIs with **Express / NestJS** — auth, RBAC, structured service layers; integrated AI APIs (Hugging Face, Gemini, OpenAI) into backend workflows
- Worked directly with founders to translate product requirements into working systems with defined backend architecture

---

## 🛠 Technical Stack

| Layer | Stack |
|---|---|
| **Languages** | TypeScript · JavaScript · Go · SQL · HTML/CSS |
| **Backend** | Node.js · Express · NestJS · BullMQ · REST APIs |
| **Frontend** | React · Next.js · TailwindCSS · Shadcn/UI · TanStack Query · React Hook Form |
| **Databases** | PostgreSQL · Redis · Firebase · Supabase |
| **Infra & DevOps** | Docker · AWS EC2 · NGINX · Prisma |
| **Tooling** | Zod · Jest · Git · GitHub · Postman · Jira |

---

## 🚀 Selected Projects

### [Sentivio — Video Emotion Analyzer](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
`Express` `PostgreSQL` `BullMQ` `Redis` `Next.js` `TypeScript`

Async video processing pipeline that extracts emotional signals and generates structured timelines and analytics dashboards.

- **BullMQ + Redis** for async job processing — heavy video workloads offloaded, fast API response times maintained under load
- Custom **signal smoothing algorithms** to denoise raw emotion predictions into stable temporal phases with averaged confidence scores
- Interactive **Next.js + TypeScript** dashboard for timeline visualization and analytics

---

### [Cortex Graph — Knowledge Graph API](https://github.com/YounessBrunno/cortex-graph-api)
`Node.js` `Express` `PostgreSQL` `Zod` `Docker`

Graph-style multi-level relationship traversal on PostgreSQL — no graph database needed.

- Engineered **graph querying with CTEs and recursive joins** for connected data exploration on relational data
- **~30% query performance improvement** via PostgreSQL full-text search (FTS) indexing
- Fully **Dockerized** — complete environment setup in under 3 minutes
- Typed API contracts via **Zod** schema validation

---

### [Velar — Perfume Discovery Platform](https://github.com/YounessBrunno/Velar-Perfume-explorer)
`Next.js` `TypeScript` `Firebase` `Supabase` `NextAuth` `TanStack Query`

Full-stack catalogue with 300+ items, admin controls, and optimized media delivery.

- **30% load time reduction** via TanStack Query caching and optimized data fetching
- Image upload pipeline cut latency from **6s → under 3s** using Supabase Storage
- Admin dashboard with **sub-250ms write performance** via NextAuth + Firestore

---

### [Vetra — AI Mock Interview Platform](https://github.com/YounessBrunno/Ai-Mock-Interview)
`Next.js` `Clerk` `Firebase` `Zod`

Simulates structured interview sessions with AI feedback, secure auth via Clerk, and Firebase session management.

---

### [Vanilla Node.js Static Server](https://github.com/YounessBrunno/vanilla-node.js-static-server)
`Node.js core` `Zero dependencies`

Apache-style HTTP static server from scratch — MIME detection, file streaming, directory listings, custom 404 pages. Built using only `http`, `fs`, `path`. No frameworks.

---

### [Vanilla Task Manager REST API](https://github.com/YounessBrunno/vanilla-node.js-task-manager-rest-api)
`Node.js core` `Zero dependencies`

Full REST API with auth, RBAC, analytics, logging, and file-based JSON storage — using only `http`, `fs`, `crypto`, `events`, `url`, `path`. No frameworks.

---

## 📊 Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YounessBrunno&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&icon_color=58a6ff&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YounessBrunno&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)

![GitHub Streak](https://streak-stats.demolab.com?user=YounessBrunno&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=21262d&ring=58a6ff&fire=58a6ff&currStreakLabel=c9d1d9&sideLabels=8b949e&dates=8b949e)

</div>

---

## 📬 Get in Touch

Open to ** backend**, **full-stack**, or **founding engineer** roles, remote preferred. If you're building something ambitious, reach out.

[![Email](https://img.shields.io/badge/younessoukhadjouu@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:younessoukhadjouu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/younessoukhadjou)

---

<div align="center">
  <sub>Open to remote opportunities worldwide</sub>
</div>
