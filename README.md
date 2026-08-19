<img width="100%" src="https://media.licdn.com/dms/image/v2/D4D22AQFdDNT0wF7QeA/feedshare-shrink_800/B4DZnTiPJ.HsAg-/0/1760190592128?e=2147483647&v=beta&t=TIR7gw8DvhVlNvj430XoNRE2szOwVuPZACPAR7O6mww" alt="Banner" />

# Backend Developer

I build and operate the services that sit behind the product — HTTP and gRPC APIs, relational data models, background workers, and the message pipelines that connect them. Most of my work lives in Go, TypeScript, and Python on Postgres and Redis, deployed as containers on Kubernetes. I care about the parts users never see directly but always feel: a query plan that stops doing a sequential scan, an idempotency key that prevents a double charge, a migration that ships without a maintenance window. I am comfortable owning a service end to end, from the schema design conversation through the on-call page at 3 a.m.

I default to boring technology and reach for something new only when I can name the specific constraint it solves. Before I optimize anything I measure it, because the bottleneck is almost never where the team assumed it was. I treat API contracts as promises — versioned, backward compatible, and documented in the same pull request as the code — and I write tests that describe behavior rather than mirror implementation. Good backend work should be legible to the next engineer, observable when it misbehaves, and cheap enough to run that nobody has to argue about the bill.

### 🛠️ Tech Stack & Skills

![Go](https://img.shields.io/badge/Go-6366f1?style=for-the-badge&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-6366f1?style=for-the-badge&logo=nestjs&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-6366f1?style=for-the-badge&logo=redis&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-6366f1?style=for-the-badge&logo=apachekafka&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-6366f1?style=for-the-badge&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-6366f1?style=for-the-badge&logo=aws&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-6366f1?style=for-the-badge&logo=terraform&logoColor=white) 

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api?username=alexrivera-ai&show_icons=true&theme=dracula" alt="GitHub Stats" />
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api/top-langs/?username=alexrivera-ai&layout=compact&theme=dracula" alt="Top Languages" />
</p>

### 💡 Expertise
API Design & Service Architecture — I design versioned REST and gRPC interfaces with clear resource boundaries, pagination rules, and error contracts that clients can depend on for years.

Data Modeling & Query Performance — I normalize schemas for correctness, then earn the speed back with the right indexes, query plans, and connection pooling rather than premature caching.

Distributed Systems & Async Messaging — I build event-driven flows with Kafka and queue-backed workers using the outbox pattern, idempotent consumers, and retry policies that survive partial failure.

Reliability & Observability — I instrument services with structured logs, traces, and RED metrics and run them against explicit SLOs, so incidents are diagnosed in minutes instead of guessed at for hours.

### 🚀 Featured Projects
Ledger API — Replaced N+1 ORM access with cursor pagination and covering indexes, dropping p99 read latency from 840 ms to 96 ms across a 12M-row transaction table.

Rate Limiter — Redis sliding-window limiter written in Go with atomic Lua scripts, sustaining 45k requests/sec at under 1 ms of added overhead per call.

Order Events — Kafka consumer group using the transactional outbox pattern and idempotency keys, delivering 3.2M order events per day with zero duplicate charges over nine months.

Auth Gateway — OAuth2 service with rotating JWTs and edge-cached JWKS verification, cutting auth-related database load by 78% and login p95 from 410 ms to 120 ms.

Job Runner — Postgres SKIP LOCKED work queue that processes 12k jobs per minute on four workers and retired a managed queue subscription costing $1,400/month.

Cluster Autoscaler — KEDA autoscaling driven by queue depth instead of CPU, trimming Kubernetes spend 41% ($3,800/month) while holding p95 processing time under 200 ms.

### 🌐 Connect With Me

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/alex-rivera-dev) [<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />](https://x.com/alexrivera_tech) [<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:alex.rivera@techcraft.io) [<img src="https://img.shields.io/badge/Website-4338CA?style=for-the-badge&logo=googlechrome&logoColor=white" />](https://alexrivera.dev)
