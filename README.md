# 👋 Hi, I'm Youness

I’m a Software Engineer focused on building scalable, high-performance, and reliable systems.

I work primarily as a **software engineer with a strong backend focus**, using **TypeScript, Node.js, Express.js, NestJS, React, Next.js, and SQL** to design and ship production-ready applications. My experience spans API design, backend architecture, frontend integration, and building end-to-end features with a strong emphasis on correctness and maintainability.

I have hands-on experience with **databases and infrastructure**, including **PostgreSQL, Redis, Firebase, Supabase, and Docker**, and I’m comfortable working with background jobs, queues, and data-intensive workflows. I care deeply about **clean architecture, system design, and performance**, and I enjoy building systems that are easy to scale, test, and evolve over time.


## 🧠 My Skills

### 🔤 Languages
[![Languages](https://skillicons.dev/icons?i=js,ts,go,postgres)](https://skillicons.dev)

---

### ⚙️ Backend
[![Backend](https://skillicons.dev/icons?i=nodejs,express,nestjs,postgres,redis,firebase,supabase,prisma,docker,nginx,aws)](https://skillicons.dev)

---

### 🎨 Frontend
[![Frontend](https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css)](https://skillicons.dev)



---

### 🛠 Tools
[![Tools](https://skillicons.dev/icons?i=git,github,postman,jest)](https://skillicons.dev)

---

## 🚀 Projects

---

### `01` &nbsp; [Sentivio — Video Emotion Analyzer](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)


`Express.js` `PostgreSQL` `BullMQ` `Redis` `Next.js` `TypeScript` `Supabase`

![backend](https://img.shields.io/badge/backend-%23EEEDFE?style=flat-square&color=EEEDFE&labelColor=3C3489&label=)
<kbd>backend</kbd> <kbd>async pipeline</kbd> <kbd>full-stack</kbd>

A professional-grade emotion intelligence system that processes any video, interprets emotional states over time, and generates timelines, summaries, and analytics — focusing solely on emotion, never identity.

- **BullMQ + Redis** async job pipeline — heavy video workloads offloaded to queues, API stays responsive under load
- Custom **signal smoothing algorithms** to denoise raw emotion predictions into stable temporal phases with averaged confidence scores
- Backend on **Express.js + PostgreSQL** deployed on Supabase; **Next.js + TypeScript** dashboard for interactive timeline visualization

[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express)](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js)](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/YounessBrunno/Sentivio-Emotion-Analyzer)

---

### `02` &nbsp; [Velar — Perfume Discovery Platform](https://github.com/YounessBrunno/Velar-Perfume-explorer)

<kbd>full-stack</kbd> <kbd>Next.js 15</kbd> <kbd>AI features in dev</kbd>

Full-stack perfume discovery platform — browse, filter, and explore 300+ fragrances with a minimal, elegant interface. AI-powered features in development: memory-based discovery (emotion → scent), perfume combiner, and blind picks.

- **30% load time reduction** via TanStack Query caching with optimized Firestore + Supabase Storage data fetching
- Image upload pipeline cut latency from **6s → under 3s** via Supabase Storage
- Admin dashboard with **sub-250ms write performance**, CRUD operations, and NextAuth-restricted access

[![Next.js](https://img.shields.io/badge/Next.js%2015-000000?style=flat-square&logo=next.js)](https://github.com/YounessBrunno/Velar-Perfume-explorer)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://github.com/YounessBrunno/Velar-Perfume-explorer)
[![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)](https://github.com/YounessBrunno/Velar-Perfume-explorer)
[![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)](https://github.com/YounessBrunno/Velar-Perfume-explorer)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/YounessBrunno/Velar-Perfume-explorer)

> `−30% load time` &nbsp;·&nbsp; `6s → <3s uploads` &nbsp;·&nbsp; `sub-250ms writes`

---

### `03` &nbsp; [Cortex Graph — Knowledge Graph API](https://github.com/YounessBrunno/cortex-graph-api)

<kbd>backend</kbd> <kbd>system design</kbd>

Transforms notes, tasks, and insights into a structured, queryable knowledge network. Graph-style multi-level relationship traversal on PostgreSQL — no graph database needed. Think of it as an API for your second brain.

- Graph querying via **CTEs + recursive relational joins** — bidirectional note links, tag associations, multi-level traversal
- **~30% query performance gain** via PostgreSQL full-text search (FTS) indexing
- Full environment up in **under 3 minutes** via Docker; typed API with Zod validation + Jest test coverage

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)](https://github.com/YounessBrunno/cortex-graph-api)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)](https://github.com/YounessBrunno/cortex-graph-api)
[![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white)](https://github.com/YounessBrunno/cortex-graph-api)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/YounessBrunno/cortex-graph-api)

> `~30% query perf gain` &nbsp;·&nbsp; `docker setup <3min`

---

### `04` &nbsp; [Path AI — Trip Planner](https://github.com/YounessBrunno/AI-Trip-Planner)

<kbd>full-stack</kbd> <kbd>AI integration</kbd>

AI-powered trip planner generating personalized travel itineraries via the Gemini API. Google OAuth authentication, real-time Firebase storage for plans and session state.

[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/YounessBrunno/AI-Trip-Planner)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://github.com/YounessBrunno/AI-Trip-Planner)
[![Gemini](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat-square&logo=google&logoColor=white)](https://github.com/YounessBrunno/AI-Trip-Planner)

---

### `05` &nbsp; [Vetra — AI Mock Interview Platform](https://github.com/YounessBrunno/Ai-Mock-Interview)

<kbd>full-stack</kbd> <kbd>AI integration</kbd>

Simulates structured interview sessions with real-time AI feedback. Secure authentication via Clerk, schema validation with Zod, session and data management backed by Firebase.

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js)](https://github.com/YounessBrunno/Ai-Mock-Interview)
[![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)](https://github.com/YounessBrunno/Ai-Mock-Interview)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://github.com/YounessBrunno/Ai-Mock-Interview)

---

### `06` &nbsp; [Axiom — SaaS Landing Page](https://github.com/YounessBrunno/)

<kbd>frontend</kbd> <kbd>motion design</kbd>

Modern SaaS landing page with rich animations and polished UI. Built with React and Shadcn/UI components; Framer Motion powers smooth, interactive micro-interactions throughout.

[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/YounessBrunno/)
[![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat-square&logo=framer&logoColor=white)](https://github.com/YounessBrunno/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/YounessBrunno/)

---

### Vanilla Node.js — Internals Series

> Two projects demonstrating low-level Node.js mastery. No frameworks, no abstractions — just the runtime.

#### `07` &nbsp; [Vanilla Static File Server](https://github.com/YounessBrunno/vanilla-node.js-static-server) &nbsp; <kbd>zero deps</kbd>

Apache-style HTTP static server from scratch — MIME type detection, efficient file streaming, dynamic directory listings with icons, custom 404 pages, access + error logging, fully configurable via `config.json`.

`http` `fs` `path` — zero frameworks

#### `08` &nbsp; [Vanilla Task Manager REST API](https://github.com/YounessBrunno/vanilla-node.js-task-manager-rest-api) &nbsp; <kbd>zero deps</kbd>

Full REST API with auth, RBAC (admin vs user), task management, analytics tracking, request logging, and file-based JSON storage — built entirely with Node.js core modules.

- Auth with hashed passwords via `crypto`, token-based route protection, role-based access control
- Analytics endpoint tracks request counts, errors, and response times stored in `analytics.json`

`http` `fs` `crypto` `events` `url` `path` — zero frameworks

---
