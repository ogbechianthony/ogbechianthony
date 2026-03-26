# Anthony Ogbechi — Senior Backend Engineer

> 4 years building production fintech and distributed systems · Node.js · NestJS · Go · PostgreSQL · Kafka · Redis

I build the backend infrastructure that moves money, delivers messages at scale, and keeps systems running when things go wrong. Based in Nigeria, working with US-headquartered teams.

Most recently: led backend engineering at **Digitpay** (Dallas, USA) — a crypto-to-fiat fintech that was accepted into the **Lisk/AyaHQ international incubator**. I designed the KYC pipeline, real-time notification infrastructure, and the merchant payment system that lets anyone pay local traders with crypto, with instant fiat settlement.

Currently building a **distributed payment engine** with Kafka, NestJS, and PostgreSQL — load-tested to 5,000 req/s with full saga-pattern transaction handling and exactly-once guarantees.

---

## What I build

```
Payment systems        — idempotent processing, saga patterns, fraud pipelines, KYC
Event-driven systems   — Kafka consumers/producers, exactly-once semantics, dead-letter queues
Real-time infrastructure — WebSockets, SSE, multi-channel notification fan-out at scale
Auth & security        — JWT, API keys, RBAC, BVN/ID/liveness verification
Multi-tenant APIs      — rate limiting, usage metering, tenant isolation
```

---

## Tech stack

**Primary**
`Node.js` `NestJS` `TypeScript` `PostgreSQL` `Redis` `Kafka` `Docker`

**Secondary**
`Go (Golang)` `MongoDB` `AWS (S3, Lambda)` `WebSockets` `SSE` `GraphQL` `Laravel`

**Observability**
`Prometheus` `Grafana` `OpenTelemetry` `Pino`

---

## Featured projects

### Distributed Payment Engine
> NestJS · Kafka · PostgreSQL · Redis · Docker · k6

Event-driven payment processing system with idempotent transaction submission, Kafka-based charge-reserve-settle saga, dead-letter queue handling for failed transactions, and Prometheus metrics. Load tested to **5,000 req/s** with p99 latency under 80ms.

→ [View repository](#) · [Architecture write-up](#)

---

### High-Throughput Notification Service
> Go · Kafka · Redis · WebSocket · Docker

Multi-channel notification service (email, SMS, push, in-app) built in Go. Token-bucket rate limiting per user (100 emails/hr), exponential backoff retries, fan-out via Kafka partitions. Designed for **10,000 notifications/second** throughput.

→ [View repository](#) · [Benchmark results](#)

---

### Multi-Tenant SaaS API Platform
> NestJS · PostgreSQL · Redis · OpenTelemetry · Prometheus · Grafana

Platform API with dual auth (JWT + API keys), per-tenant rate limiting, usage metering by billing cycle, and full distributed tracing with trace IDs across all log lines. Includes live Grafana dashboard.

→ [View repository](#)

---

### Real-Time Collaborative Backend
> NestJS · Socket.io · Redis · Yjs (CRDT) · PostgreSQL

WebSocket-powered collaborative backend with CRDT-based conflict resolution (Yjs), presence indicators, offline sync queue, and horizontal scaling via Redis pub/sub adapter.

→ [View repository](#)

---

## Production experience highlights

| What I built | Where | Scale / outcome |
|---|---|---|
| KYC verification pipeline (ID + BVN + liveness) | Digitpay | Automated 95% of onboarding, reduced fraud exposure |
| Crypto-to-fiat merchant payment system | Digitpay | Accepted into Lisk/AyaHQ international incubator |
| Multi-channel notification module (WS + SSE + push) | Digitpay | Real-time delivery across 5 channels |
| Instructor-led course marketplace backend | Hackpiy / CodelandCS | Supported hundreds of paying students |
| Geolocation-based service matching engine | 360 Auto | Reduced service fulfillment time significantly |
| Serverless GraphQL learning platform | Uber Education | AWS Lambda + API Gateway + Rapyd cross-border payments |

---

## Currently levelling up

- **Go** — building production services, concurrency patterns, goroutines/channels
- **Distributed systems** — DDIA chapters 5–9, consensus algorithms, failure modes
- **System design** — designing one system per week (payment processor, rate limiter, chat system)
- **DSA** — NeetCode roadmap, solving in TypeScript and Go

---

## Writing

I write about backend engineering, fintech systems, and distributed architecture.

→ [Medium / Dev.to](#) *(link your blog here)*


📧 ogbechiarinze@gmail.com · [LinkedIn](#) · [GitHub](https://github.com/ogbechianthony)

