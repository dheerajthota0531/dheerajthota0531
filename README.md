# Hey, I'm Thota Dheeraj 👋

**Backend Engineer → Systems Engineering (Rust)**

2.5 years building and shipping production systems — including two founder stints where I was the only engineer in one and co-founded the other one. Built MakeClient (SaaS for CA firms, paying users) makeclient.com and Winqroo (B2C MVP), shipped both, wound both down. Now focused on systems engineering in Rust and AI Agents.

Currently deep in distributed backend infrastructure — job queues, concurrent workers, async systems.

## What I'm Building Now

**Distributed Job Queue in Rust** — Axum, PostgreSQL (`SELECT FOR UPDATE SKIP LOCKED`), Redis atomic rate limiting, SSE, JWT auth. Concurrent worker pool with retry logic and dead letter queue.
🔗 [Live](https://job-queue-production.up.railway.app) · [GitHub](https://github.com/dheerajthota0531/job-queue)

---

## Tech

**Rust** — Axum, Tokio, SQLx, Serde, async/await, ownership, borrowing, lifetimes, Arc/Mutex, mpsc channels

**Backend** — Node.js, Express.js, REST APIs, PostgreSQL, MySQL, Redis

**Cloud & DevOps** — Docker, GitHub Actions, Nginx, Linux, AWS, GCP, DigitalOcean

**Frontend** — React.js, TypeScript, JavaScript

**Other** — Python, FastAPI, pgvector, NLP pipelines

---

## Projects

### Distributed Job Queue — Rust
Production-grade distributed job queue. Core pattern: `SELECT FOR UPDATE SKIP LOCKED` for distributed mutual exclusion across concurrent workers — no Kafka, no RabbitMQ. Atomic Redis rate limiting per worker using pipelined INCR + EXPIRE, JWT auth, retry logic, dead letter queue, real-time SSE.
🔗 [Live](https://job-queue-production.up.railway.app) · [GitHub](https://github.com/dheerajthota0531/job-queue)

---

### Drift — PostgreSQL Schema Diff CLI — Rust
Connects to two PostgreSQL databases and produces a side-by-side colored tree diff of their schemas. Recursive diffing algorithm with Added/Removed/Modified/Unchanged status per node. Built during production work at Uzvi Services.
🔗 [GitHub](https://github.com/dheerajthota0531/drift)

---

### Streaming CLI Chat Agent — Rust
Terminal chat agent that streams responses token-by-token from a local LLM running on Ollama using `reqwest` byte streaming and async Tokio. No buffering — output appears in real time as the model generates.
🔗 [GitHub](https://github.com/dheerajthota0531/CLI_CHAT_AGENT)

---

### Concurrent File Processor — Rust
Multi-threaded CLI that reads a folder of `.txt` files concurrently, counts word frequencies per file, and outputs results sorted by count. Uses `Arc<Mutex<HashMap>>`, `thread::spawn`, and `join()`.
🔗 [GitHub](https://github.com/dheerajthota0531/rust_threads)

---

### Task Manager CLI with Writer Thread — Rust
CLI task manager with persistent JSON storage via a dedicated writer thread pattern. Main thread sends `WriteCommand` variants through `mpsc` channel; writer thread owns all disk writes.
🔗 [GitHub](https://github.com/dheerajthota0531/Rust-Smart-CLI)

---

### Expense Tracker CLI — Rust
CSV-backed expense tracker with income/expense categorisation, financial summary, and deficit/surplus status. Uses `serde`, custom enums with derive macros, and pattern matching.
🔗 [GitHub](https://github.com/dheerajthota0531/expense-tracker-cli)

---

### MakeClient — Practice Management SaaS
Built and deployed a SaaS for CA firms solo — REST APIs, RBAC, billing workflows, document management. Node.js, React, MySQL, Docker, AWS. Ran in production with paying users.

---

### MOEAP Employee Management System — Live
Government employee management system for the Ministry of Energy, Andhra Pradesh. RBAC, grievance workflows, internal admin tools. Built and deployed solo in under 3 weeks. Still running.
🔗 [moeap.com](https://moeap.com)

---

## Publications

- *A Comprehensive Review of Deepfake Detection Using Deep Learning Techniques* — ETJ, Apr 2025
- *A Conversational Chat Interface with Specific Trained Data* — Jun 2024

---

## Connect

[![Email](https://img.shields.io/badge/Email-dheeraj.thota.0531%40gmail.com-red?logo=gmail)](mailto:dheeraj.thota.0531@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-thotadheeraj-blue?logo=linkedin)](https://linkedin.com/in/thotadheeraj)
[![Portfolio](https://img.shields.io/badge/Portfolio-dheerajthota0531.github.io-0A66C2)](https://dheerajthota0531.github.io)
