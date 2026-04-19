# Youness Oukhadjou

I build backend systems that don’t fall apart when they start to matter.

Most of my work sits at the boundary between **product requirements and system constraints** — turning vague ideas into structured, predictable, and scalable systems.

---

## How I think

I care less about frameworks and more about:

- where state lives
- what guarantees actually hold
- how systems behave under failure
- how complexity grows over time

I optimize for:

- **clarity over cleverness**
- **explicitness over magic**
- **systems that are easy to debug at 3am**

A lot of early-stage systems don’t fail because of scale —  
they fail because they become impossible to reason about.

I try to prevent that.

---

## What I’ve done recently

### Founding Engineer — early-stage product

Came into a messy codebase and turned it into something we could actually build on:

- collapsed scattered services into a **structured monorepo**
- designed a **modular monolith (NestJS + PostgreSQL)** instead of jumping to microservices too early
- built core backend systems that defined the product’s data model and behavior
- shipped a **Dockerized deployment (EC2 + Nginx)** with a single entry point
- implemented a **transaction system in Go** with idempotency + strict correctness guarantees
- introduced a **BFF layer (Next.js)** to stop frontend/backend coupling from getting worse

The goal wasn’t “perfect architecture” —  
it was **making the system stable enough to evolve without constant rewrites**.

---

### Freelance work

Worked directly with founders shipping products from scratch:

- built and shipped **7+ fullstack apps**
- designed APIs with **auth, RBAC, and clear service boundaries**
- integrated AI APIs into real workflows (not demos)
- cleaned up systems that were already getting hard to maintain

---

## Selected systems

### Sentivio — async video processing

A system that processes video and extracts structured emotional timelines.

- heavy work moved to **queues (Redis + BullMQ)**  
- API stays fast while jobs run in the background  
- built custom logic to turn noisy predictions into usable signals  

Main problem: **CPU-heavy workloads without killing API performance**

---

### Cortex Graph — relational graph layer

- modeled connected data using **PostgreSQL (not a graph DB)**  
- built query patterns for multi-level traversal  
- used CTEs + FTS to keep performance acceptable  

Main problem: **getting graph-like behavior without adding new infrastructure**

---

### Velar — fullstack system

- handled **data consistency across Firebase + Supabase + API layer**  
- reduced load time by ~30%  
- built admin workflows with predictable writes  

Main problem: **keeping data flow sane across multiple systems**

---

## What I care about

- systems that don’t become fragile after 3 features  
- codebases that another engineer can understand quickly  
- avoiding “smart” solutions that age badly  
- being able to answer: *“what happens if this fails?”*  

---

## Current direction

Leaning more into:

- distributed systems (when they’re actually needed)  
- performance-sensitive backend work  
- deeper use of Go for critical paths  
- system design that holds up past MVP stage  

---

## Contact

github.com/YounessBrunno  
linkedin.com/in/youness-oukhadjou  
younessoukhadjouu@gmail.com
