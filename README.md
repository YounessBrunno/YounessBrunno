<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0d2137,100:0d1117&height=180&section=header&text=Youness%20Oukhadjou&fontSize=42&fontColor=58a6ff&fontAlignY=38&desc=Software%20Engineer%20%E2%80%94%20Backend%20%C2%B7%20Systems%20%C2%B7%20Infrastructure&descAlignY=58&descSize=16&descColor=8b949e" width="100%"/>
</div>

<div align="center">

[![Email](https://img.shields.io/badge/younessoukhadjouu@gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=161b22)](mailto:younessoukhadjouu@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=161b22)](https://linkedin.com/in/younessoukhadjou)
&nbsp;
[![GitHub](https://img.shields.io/badge/@YounessBrunno-0d1117?style=flat-square&logo=github&logoColor=white&labelColor=161b22)](https://github.com/YounessBrunno)
&nbsp;
![Status](https://img.shields.io/badge/Open%20to%20Senior%20%2F%20Staff%20Roles-%23238636?style=flat-square&labelColor=1a7f37)

</div>

<br/>

---

## 👋 About Me

I'm a software engineer with a strong **backend focus** — I build scalable, high-performance, and reliable systems that are easy to evolve over time.

My work spans **API design, backend architecture, async job pipelines, transaction processing, and infrastructure** — with a constant emphasis on correctness, clean architecture, and system design. I've worked as a **Founding Engineer**, where I owned the entire technical foundation: monorepo structure, service boundaries, deployment topology, and data modeling, from the ground up.

I have hands-on experience with **databases and infrastructure** — PostgreSQL, Redis, Firebase, Supabase, Docker, and AWS — and I'm comfortable working across background job systems, queues, and data-intensive workflows.

When the product demands it, I ship the frontend too — primarily **Next.js and React** — so features land complete without handoff friction. I care deeply about **performance, testability, and systems that scale** without becoming a maintenance burden.

---

## 💼 Experience

### Evu &nbsp;—&nbsp; Founding Software Engineer
`Dec 2025 – Present` &nbsp;·&nbsp; Remote, United States

> Early-stage startup. Joined as founding engineer — shaped the entire technical foundation from zero.

- Restructured a fragmented codebase into a **multi-service monorepo** (NestJS · Next.js · Go) — standardized cross-service development and improved long-term maintainability
- Designed a **modular monolith architecture** (NestJS + PostgreSQL) with clear service boundaries, balancing MVP velocity with future scalability
- Built a **transaction processing service in Go** with atomic operations, idempotent handling, and persistent state logging for full ledger correctness
- Deployed a cost-efficient **multi-container stack on EC2** — Dockerized Nginx as a single reverse proxy routing to internal services; full local setup under 9 minutes
- Implemented a **Next.js BFF layer** to aggregate client-side data and decouple frontend logic from backend services
- Built the **admin dashboard** using server components, caching, and partial prerendering to reduce render latency on critical paths
- Structured engineering workflows in **Jira** for coordinated multi-contributor development during MVP phase

<br/>

### Freelance &nbsp;—&nbsp; Software Engineer
`Nov 2024 – Present` &nbsp;·&nbsp; Remote

- Delivered **7+ production full-stack applications** (Next.js + Node.js) — owned backend architecture, frontend implementation, and third-party integrations end-to-end
- Built APIs with **Express / NestJS** including auth, RBAC, and structured service layers; integrated AI APIs (Hugging Face, Gemini, OpenAI) into backend workflows
- Collaborated with founders to translate product requirements into working systems with defined architecture

---

## 🛠 Tech Stack

### 🔤 Languages
[![Languages](https://skillicons.dev/icons?i=ts,js,go,postgres,html,css)](https://skillicons.dev)

---

### ⚙️ Backend
[![Backend](https://skillicons.dev/icons?i=nodejs,express,nestjs,redis,prisma,nginx,aws,docker)](https://skillicons.dev)

---

### 🎨 Frontend
[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,framer)](https://skillicons.dev)

---

### 🗄️ Databases & Services
[![Databases](https://skillicons.dev/icons?i=postgres,redis,firebase,supabase)](https://skillicons.dev)

---

### 🧰 Tools
[![Tools](https://skillicons.dev/icons?i=git,github,postman,jest,vscode)](https://skillicons.dev)

---

## 🚀 Selected Projects

### [Sentivio — Video Emotion Analyzer](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
`Express` `PostgreSQL` `BullMQ` `Redis` `Next.js` `TypeScript`

Async video processing pipeline that extracts emotional signals and generates structured timelines and analytics — designed as a professional-grade emotion-insight engine, not an identity system.

- **BullMQ + Redis** for async job offloading — heavy video workloads processed in background, fast API response times maintained under load
- Custom **signal smoothing and aggregation algorithms** to denoise raw emotion predictions into stable temporal phases with averaged confidence scores
- Interactive **Next.js + TypeScript** dashboard for timeline visualization, phase breakdowns, and analytical summaries

---

### [Cortex Graph — Knowledge Graph API](https://github.com/YounessBrunno/cortex-graph-api)
`Node.js` `Express` `PostgreSQL` `Zod` `Docker`

Transforms notes, tasks, and insights into a structured, queryable knowledge network — graph-style traversal on PostgreSQL, no graph database required.

- Engineered **multi-level relationship traversal** via CTEs and recursive relational joins
- **~30% query performance improvement** using PostgreSQL full-text search (FTS) indexing
- Fully **Dockerized** — complete environment up in under 3 minutes
- Typed API surface via **Zod** schema validation, reducing runtime errors at the boundary

---

### [Velar — Perfume Discovery Platform](https://github.com/YounessBrunno/Velar-Perfume-explorer)
`Next.js` `TypeScript` `Firebase` `Supabase` `NextAuth` `TanStack Query`

Full-stack catalogue platform with 300+ items, admin controls, and optimized media delivery.

- **30% load time reduction** via TanStack Query caching and optimized data fetching strategies
- Image upload pipeline cut latency from **6s → under 3s** via Supabase Storage
- Admin dashboard with **sub-250ms write performance**, CRUD operations, NextAuth authentication

---

### [Vetra — AI Mock Interview Platform](https://github.com/YounessBrunno/Ai-Mock-Interview)
`Next.js` `Clerk` `Firebase` `Zod`

Simulates structured interview sessions with AI-driven feedback. Secure auth via Clerk, schema validation with Zod, and session management backed by Firebase.

---

### [Vanilla Node.js Static Server](https://github.com/YounessBrunno/vanilla-node.js-static-server)
`Node.js core` `Zero dependencies`

Apache-style HTTP static file server built from scratch — MIME type detection, efficient file streaming, dynamic directory listings, custom 404 pages. Pure `http`, `fs`, `path`. No frameworks.

---

### [Vanilla Task Manager REST API](https://github.com/YounessBrunno/vanilla-node.js-task-manager-rest-api)
`Node.js core` `Zero dependencies`

Full REST API with auth, RBAC, analytics, event logging, and file-based JSON storage — built entirely with `http`, `fs`, `crypto`, `events`, `url`, `path`. Zero frameworks. A study in Node.js internals.

---

## ⚡ Currently

```ts
const now = {
  building:  "Production infrastructure @ Evu — Go services, NestJS monolith, EC2 deployments",
  exploring: "Advanced PostgreSQL internals, distributed systems patterns, system design at scale",
  reading:   "Designing Data-Intensive Applications — Kleppmann",
  open_to:   "Senior Backend · Full-Stack · Founding Engineer roles (remote)",
};
```

---

## 📬 Get in Touch

Building something ambitious? I'd like to hear about it.

[![Email](https://img.shields.io/badge/younessoukhadjouu@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:younessoukhadjouu@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/younessoukhadjou)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0d2137,100:0d1117&height=80&section=footer" width="100%"/>
</div>
