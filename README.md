<img width="100%" src="https://github.blog/wp-content/uploads/2024/04/Enterprise-DarkMode-2-3.png?fit=1200%2C630" alt="Banner" />

# Full Stack Developer

I build and ship complete web products — from the database schema and API contracts all the way to the accessible, responsive interface a user actually touches. Most of my work lives in the TypeScript ecosystem: Next.js and React on the front end, Node with Express or NestJS behind it, and Postgres accessed through Prisma. I care about the unglamorous parts that decide whether a product survives contact with real traffic: pagination that doesn't fall over at a million rows, background jobs that retry safely, auth flows that handle the edge cases, and CI that catches regressions before a customer does. I've taken projects from an empty repo to production on AWS and Vercel, and I've also inherited five-year-old codebases and made them fast again.

I believe the fastest way to build something good is to make it observable and reversible. I ship small changes behind feature flags, instrument before I optimize, and let profiler output rather than intuition decide what gets rewritten. I write the tests that would have caught last month's incident instead of chasing a coverage number, and I treat a clear error message or a well-named migration as part of the feature, not as overhead. Code is read far more often than it is written, so I optimize for the engineer who opens the file six months from now — including when that engineer is me.

### 🛠️ Tech Stack & Skills

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-6366f1?style=for-the-badge&logo=express&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-6366f1?style=for-the-badge&logo=prisma&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-6366f1?style=for-the-badge&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-6366f1?style=for-the-badge&logo=githubactions&logoColor=white) 

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api?username=alexrivera-ai&show_icons=true&theme=radial" alt="GitHub Stats" />
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api/top-langs/?username=alexrivera-ai&layout=compact&theme=radial" alt="Top Languages" />
</p>

### 💡 Expertise
Frontend Architecture — I build React and Next.js interfaces with server components, streaming SSR, and a strict accessibility and Core Web Vitals budget so pages stay fast on mid-range mobile devices.

API & Backend Services — I design REST and GraphQL services in Node and TypeScript with layered validation, idempotent write endpoints, rate limiting, and queued background jobs for anything slower than a request cycle.

Data Modeling & Persistence — I model relational schemas in Postgres, write and review migrations, tune indexes and query plans, and use Redis for caching and session state where it measurably cuts response time.

Deployment & Reliability — I containerize services with Docker, automate build, test, and release through GitHub Actions, and keep systems observable with structured logging, dashboards, and alerts tied to real user-facing symptoms.

### 🚀 Featured Projects
Commerce Storefront — Rebuilt a headless storefront on the Next.js App Router with ISR and edge caching, cutting largest contentful paint from 4.1s to 1.2s and lifting checkout conversion by 18%.

Realtime Board — Implemented a collaborative whiteboard using WebSockets with Yjs CRDT merging and Redis pub/sub fan-out, sustaining 200 concurrent editors per room at under 80ms sync latency.

Billing API — Designed an idempotent Stripe webhook pipeline with a Postgres outbox table and exponential-backoff retries, eliminating duplicate charges and raising failed-invoice recovery from 61% to 94%.

Query Optimizer — Profiled the ten slowest endpoints with pg_stat_statements and added partial and composite indexes, dropping p95 API latency from 870ms to 130ms with no application rewrite.

Design System — Shipped a 42-component Radix and Tailwind library with Storybook docs and Chromatic visual regression tests, reducing new feature UI build time by about 40% across four product teams.

Deploy Pipeline — Replaced a manual release process with multi-stage Docker builds and a GitHub Actions test matrix, taking deploys from 35 minutes to 6 and enabling ten production releases a week.

### 🌐 Connect With Me

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/alex-rivera-dev) [<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />](https://x.com/alexrivera_tech) [<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:alex.rivera@techcraft.io) [<img src="https://img.shields.io/badge/Website-4338CA?style=for-the-badge&logo=googlechrome&logoColor=white" />](https://alexrivera.dev)
