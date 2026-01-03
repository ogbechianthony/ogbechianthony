# OGBECHI Anthony Arinze

Senior Backend Engineer focused on building systems that work under real constraints: unreliable third-party services, inconsistent data, tight timelines, and production traffic.

I have 4+ years of experience building backend systems across fintech, payments, real-time platforms, and Web3-adjacent products. Most of my work sits in the uncomfortable middle where requirements change mid-flight, failures are normal, and performance and correctness matter more than clean abstractions.

My core background is Node.js (NestJS) and Laravel. I am currently expanding into Go and blockchain infrastructure, with an emphasis on throughput, correctness, and operational reliability.

---

## Current Focus

- Building high-performance blockchain indexers and ingestion pipelines using Go.
- Upscaling my blockchain development skills, focusing on Solidity, gas optimization, and smart contract security auditing.

Indexing and blockchain infra work is mostly about edge cases: reorgs, partial failures, backfills, duplicate events, and making sure retries don’t corrupt state.

---

## What I Optimize For

- Systems that degrade gracefully instead of failing loudly.
- Clear data ownership and auditability, especially in financial systems.
- Idempotent flows where retries are unavoidable.
- Pragmatic architecture decisions that fit team size, deadlines, and cost.

---

## Core Stack

### Backend
- Node.js, NestJS, Express
- PHP, Laravel, Laravel Lumen
- REST APIs, GraphQL

### Data & Caching
- PostgreSQL
- MySQL
- MongoDB
- Redis

### Real-Time & Messaging
- WebSockets
- Server-Sent Events (SSE)

### Infrastructure
- Docker
- AWS (S3, Lambda, API Gateway)
- Render, DigitalOcean

### Tooling
- Git, GitHub

---

## Selected Experience

### Senior Backend Developer — Digitpay Finance  
Oct 2024 – Present

Fintech crypto payments platform operating across the US and Nigeria.

- Designed and implemented a KYC pipeline combining BVN, ID verification, and liveness checks.
- Automated most of user onboarding while still handling manual fallbacks for provider failures and inconsistent responses.
- Built real-time notification infrastructure using WebSockets and SSE.
- Worked on crypto-to-fiat payment flows where idempotency, reconciliation, and audit trails were mandatory.
- Collaborated closely with the CTO during a product pivot, revisiting assumptions that did not hold in production.

Tech: NestJS, PostgreSQL, Redis, AWS S3, WebSockets

The hard part was not writing APIs. It was handling unreliable third-party services, retry storms, and making sure users didn’t get stuck in broken states.

---

### Backend Engineer — Hackpiy Software Solutions  
Dec 2022 – Oct 2024

Worked across multiple products with very different constraints, including education platforms, e-commerce, and on-demand services.

- Built and maintained REST and GraphQL APIs.
- Integrated payment providers (Paystack, Rapyd).
- Implemented geo-fencing attendance systems.
- Optimized database access patterns and introduced Redis caching where it actually helped.

Tech: Laravel, Laravel Lumen, Node.js, MySQL, MongoDB, AWS Lambda

Most complexity came from scaling systems that were not initially designed to scale, while keeping existing users unbroken.

---

### Freelance / Contract Work (Selected)

- Poultry management platform with real-time operational tracking.
- Digital billing and wallet systems.
- Social platforms with real-time chat and notifications.
- Web3 token distribution systems.

These projects reinforced a consistent lesson: production systems are shaped more by failure modes than by happy paths.

---

## Education

B.Sc. Computer Science  
National Open University of Nigeria (studies currently paused)

---

## Contact

Email: ogbechiarinze@gmail.com  
GitHub: https://github.com/ogbechiarinze

---

I’m interested in backend problems where correctness, performance, and operational reality matter more than trends.
