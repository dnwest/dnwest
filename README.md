### Hi there, I'm Cristian 👋
#### Senior Software Engineer | Backend · Cloud · Distributed Systems

Over 15 years building enterprise software. I design and ship resilient,
event-driven backends, distributed systems that stay observable and keep running
when things go wrong. Node.js / TypeScript on AWS, with production-grade DevOps
around them.

🎮 **See it running:** [break my system live](https://www.dnwest.dev/tetris). A
playable game whose leaderboard survives its own database going down.

---

### 🚀 Core Expertise
*   **Architecture:** Event-Driven Design, Distributed Systems, Microservices, Modular Monoliths, Clean / Hexagonal Architecture.
*   **Backend:** Node.js, NestJS, TypeScript, PostgreSQL, Redis, Next.js.
*   **Cloud & DevOps:** AWS (SQS/SNS, Lambda, EC2, S3, RDS), Docker, Terraform, GitHub Actions, CI/CD.
*   **Resilience & Performance:** Circuit Breakers, DLQs, idempotency, graceful shutdown, observability, load testing with k6.

---

### 🛠 Tech Stack
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/next.js-000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)

---

### 🏗️ Featured Projects

| Project | Description | Key Technologies |
|---------|-------------|-------------------|
| 🚩 [**conveyor**](https://github.com/dnwest/conveyor) *(flagship, in active development)* | End-to-end, event-driven order pipeline: a resilient SQS/SNS worker (retries, backoff, DLQ, circuit breaker, idempotency) behind a NestJS API with Swagger, observed live through a Next.js operations console. Unifies the two patterns below into one full-stack product. k6 on a local stack (LocalStack standing in for AWS): held 300 orders/s with 0% errors, end-to-end p95 of 76 ms. | NestJS, AWS SQS/SNS, Next.js, PostgreSQL, Turborepo |
| [resilient-node-microservice](https://github.com/dnwest/resilient-node-microservice) | Synchronous payment API demonstrating fault tolerance: circuit breaker with a fast fallback, rate limiting, fail-fast config and graceful shutdown, provisioned with Terraform. | Node.js, Express, Opossum, Zod, Pino, Terraform |
| [event-driven-order-processor](https://github.com/dnwest/event-driven-order-processor) | Asynchronous worker built around the failure modes of messaging: SNS fan-out, SQS consumption, circuit breaker, retries with backoff, Redis-backed idempotency and a Dead Letter Queue, with KMS encryption and least-privilege IAM declared in Terraform. | AWS SQS/SNS, Redis, Terraform, Prometheus |
| [Resilient Tetris](https://www.dnwest.dev/tetris) *(live demo)* | Inject a database outage in your own session and watch the circuit breaker open, the leaderboard fall back to its last known good state and scores wait in an idempotent outbox. | Next.js, PostgreSQL, Circuit Breaker, Outbox |

---

### 📫 Let's Connect
*   **Portfolio:** [www.dnwest.dev](https://www.dnwest.dev)
*   **Blog:** [graceful degradation series and more](https://www.dnwest.dev/blog)
*   **Résumé:** [PDF](https://www.dnwest.dev/cv/Cristian-Fernandes-CV.pdf)
*   **LinkedIn:** [linkedin.com/in/cristianfernandes-dev](https://www.linkedin.com/in/cristianfernandes-dev/)

Open to senior full-time roles and to focused projects or consulting engagements.
