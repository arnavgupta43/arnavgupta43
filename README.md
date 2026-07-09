![MasterHead](https://user-images.githubusercontent.com/10498744/210012254-234538ff-d198-48aa-8964-37e6fd45d227.gif)

<h1 align="center">Arnav Kumar Gupta</h1>
<p align="center"><i>Backend Engineer · CS Student · Bangalore</i></p>

<p align="center">
  <a href="https://github.com/arnavgupta43"><img src="https://img.shields.io/badge/GitHub-arnavgupta43-181717?style=flat-square&logo=github" /></a>
  <a href="https://www.linkedin.com/in/arnavkumargupta"><img src="https://img.shields.io/badge/LinkedIn-arnavkumargupta-0A66C2?style=flat-square&logo=linkedin" /></a>
  <a href="https://leetcode.com/arnavgupta_43"><img src="https://img.shields.io/badge/LeetCode-arnavgupta_43-FFA116?style=flat-square&logo=leetcode&logoColor=white" /></a>
  <a href="https://medium.com/@arnavkumargupta777"><img src="https://img.shields.io/badge/Medium-arnavkumargupta777-000000?style=flat-square&logo=medium" /></a>
  <img src="https://komarev.com/ghpvc/?username=arnavgupta43&style=flat-square&color=0e75b6" />
</p>

---

I build **scalable backend systems** — from payment gateways and LLM rate limiters to high-concurrency inventory engines sustaining **~1.6K RPS**. Currently a 3rd-year CS student, working on wealth-domain platform infrastructure and AI assistant tooling at Smallcase Technologies.

<br>

<table align="center">
  <tr>
    <td align="center"><b>3+</b><br><sub>Internships</sub></td>
    <td align="center"><b>~1.6K</b><br><sub>RPS Achieved</sub></td>
    <td align="center"><b>4M+</b><br><sub>Records Migrated</sub></td>
    <td align="center"><b>9.62 / 10</b><br><sub>CGPA</sub></td>
  </tr>
</table>

<br>

---

## Work Experience

**Backend Engineering Intern — [Smallcase](https://smallcase.com)** &nbsp;`Mar 2026 – Present`

- Designed (HLD/LLD) and implemented the wealth-domain subset of a platform **account deletion** feature, orchestrating data purging across **15+ database collections** and AWS-backed microservices to process **3,000+ user offboarding requests** during its pilot phase.
- Architected a centralized event-tracking backend with smart client-side caching to resolve downstream data anomalies and minimize network load; built **Apache Airflow** pipelines using streams and bulkWrite batches to migrate and backfill **4M+ users in under 15 minutes**.
- Expanded an AI assistant's MCP with new tools using compact JSON (**30% token reduction**), while optimizing **16 existing APIs** by stripping UI metadata — saving **~1.5M tokens** platform-wide.
- Re-engineered the **Experian** credit consent renewal flow to mitigate API deprecations, implementing **Kafka** event emitters and updated Airflow jobs to prevent mass consent expiration for thousands of active users.
- Engineered a dependency-injected logging abstraction for a core credit SDK, restoring **Kibana** indexing for 20% of the platform's previously unindexed production logs.

<br>

**Software Engineering Intern — CodeWiser** &nbsp;`Jan 2026 – Feb 2026`

- Integrated **Razorpay** subscriptions for 4 paid plan tiers (2 monthly, 2 yearly) with webhook-based billing automation, helping the MVP generate its first revenue.
- Designed a backend quota-tracking system for LLM APIs using **PostgreSQL row-level locking**, strictly enforcing tier-based usage limits and preventing race conditions to optimize platform API costs.
- Refactored **NextAuth** session handling, eliminating redundant user-fetch API calls and significantly reducing client-side navigation latency.

<br>

**Software Engineering Intern — Gullak Money** &nbsp;`Apr 2025 – May 2025`

- Enhanced codebase stability and functionality by implementing new features, debugging critical issues, and writing dedicated unit tests.

---

## Key Projects

### ⚡ Flash-Sale Reservation Engine — High-Concurrency Inventory System
`Node.js` `Express` `Redis` `PostgreSQL` `Redis Streams`

- Built a high-concurrency inventory reservation API using optimistic Redis transactions **(WATCH/MULTI)** and TTL-based holds to prevent oversells.
- Designed an event-driven workflow with **Redis Streams** and a worker service to process hold lifecycle events, with idempotency safeguards and transactional writes to persist state and ensure safe retries.
- Validated zero-oversell invariants via **k6 load testing** (100 VUs) — sustained **~1.6K RPS at p95 <35ms**.

### 🐇 MicroTasker — Event-Driven Task Management Backend
`Node.js` `Express` `MongoDB` `RabbitMQ` `Docker` `JWT`

- Designed an event-driven backend with 3 decoupled services and 3 domain events using **RabbitMQ** for async user, task, and notification workflows.
- Implemented a reliable notification worker with durable queues, explicit message acknowledgments, and graceful shutdown (SIGTERM/SIGINT).
- Added production-grade observability via structured JSON logging with **request correlation IDs** and Docker-integrated healthcheck endpoints.

---

## Technical Skills

**Backend Development**
&nbsp; APIs, auth, business logic, and scalable services.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

<br>

**Databases, Messaging & Infra**
&nbsp; Data modeling, persistence, event pipelines, and deployment-ready workflows.

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=for-the-badge&logo=amazons3&logoColor=white)

<br>

**Tools & Observability**
&nbsp; Daily workflow tools for shipping, debugging, and iteration.

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Education

**CHRIST University, Bangalore** — B.Tech in Computer Science &nbsp;`Jun 2023 – May 2027`
CGPA: **9.62 / 10**
Coursework: Data Structures & Algorithms, Operating Systems, Object-Oriented Programming, Computer Networks, Database Management Systems, Cloud Computing

---

## Technical Writing

<table>
  <tr>
    <td width="50%">
      <a href="https://medium.com/@arnavkumargupta777/strong-consistency-in-distributed-systems-raft-algorithm-e366649ffb1e">
        <img width="100%" height="420" src="https://github.com/user-attachments/assets/d8eab445-0a9d-4151-b1c1-006fa5e97262" />
      </a>
      <br>
      <b><a href="https://medium.com/@arnavkumargupta777/strong-consistency-in-distributed-systems-raft-algorithm-e366649ffb1e">Strong Consistency: The Raft Algorithm</a></b>
      <br>
      <sub>A deep dive into leader election, log replication, and safety guarantees in distributed systems.</sub>
    </td>
    <td width="50%">
      <a href="https://medium.com/@arnavkumargupta777/merge-islands-game-design-and-analysis-of-algorithms-0303a537d78d">
        <img width="100%" height="420" src="https://github.com/user-attachments/assets/1871b9fe-e3dd-4339-ab82-7df57ac17256" />
      </a>
      <br>
      <b><a href="https://medium.com/@arnavkumargupta777/merge-islands-game-design-and-analysis-of-algorithms-0303a537d78d">Merge Islands: DSU Algorithm</a></b>
      <br>
      <sub>Designing a game using Disjoint Set Union with path compression and algorithmic analysis.</sub>
    </td>
  </tr>
</table>

---

## Coding Stats

<div align="center">
  <a href="https://leetcode.com/arnavgupta_43">
    <img src="https://leetcard.jacoblin.cool/arnavgupta_43?theme=dark&font=baloo&ext=heatmap" alt="Arnav's LeetCode Stats" />
  </a>
</div>

---
