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

I build **scalable backend systems** — from payment gateways and LLM rate limiters to high-concurrency inventory engines sustaining **~1.6K RPS**. Currently a 3rd-year CS student, optimizing MCP endpoints at Smallcase Technologies.

<br>

<table align="center">
  <tr>
    <td align="center"><b>3+</b><br><sub>Internships</sub></td>
    <td align="center"><b>~1.6K</b><br><sub>RPS Achieved</sub></td>
    <td align="center"><b>~1.5M</b><br><sub>Tokens Saved</sub></td>
    <td align="center"><b>3.85 / 4</b><br><sub>CGPA</sub></td>
  </tr>
</table>

<br>

---

## Work Experience

**Backend Engineering Intern — [Smallcase Technologies](https://smallcase.com)** &nbsp;`Apr 2026 – Present`

- Optimized **16 wealth-domain API endpoints** for the in-house AI assistant's MCP, achieving a **30–45% token reduction** per endpoint.
- Saved **~1.5M tokens platform-wide** and decreased API bandwidth, with comprehensive end-to-end tests guaranteeing zero feature degradation.
- Monitored production health via **Sentry**, debugging and patching live anomalies to maintain high API reliability and uptime.

<br>

**Software Engineering Intern — CodeWiser** &nbsp;`Jan 2026 – Feb 2026`

- Integrated **Razorpay** for subscription-based plans with webhook listeners automating recurring billing and access control.
- Designed a **rate-limiting system** for LLM APIs using PostgreSQL row-level locking and transactional integrity, enforcing usage quotas at scale.
- Refactored NextAuth session handling — achieved a **100% reduction** in redundant user-fetch API calls during page navigation.

<br>

**Software Engineering Intern — Gullak Money** &nbsp;`Apr 2025 – May 2025`

- Reduced critical production defects through rigorous debugging and dedicated unit tests.
- Owned end-to-end implementation and deployment of a utility service, delivering ahead of schedule.

---

## Key Projects

### ⚡ Flash-Sale Reservation Engine — High-Concurrency Inventory System
`Node.js` `Express` `Redis` `PostgreSQL` `Redis Streams`

- Built a high-concurrency inventory reservation API using optimistic Redis transactions **(WATCH/MULTI)** and TTL-based holds to prevent oversells.
- Designed an event-driven workflow with **Redis Streams** and a worker service to process hold lifecycle events and persist state in Postgres.
- Validated zero-oversell invariants via **k6 load testing** (100 VUs) — sustained **~1.6K RPS at p95 <35ms**.

### 🐇 MicroTasker — Event-Driven Task Management Backend
`Node.js` `Express` `MongoDB` `RabbitMQ` `Docker` `JWT`

- Designed an event-driven microservices architecture using **RabbitMQ** for loose coupling and async workflows across services.
- Implemented a reliable notification service with durable queues, explicit message acknowledgments, and graceful shutdown (SIGTERM/SIGINT).
- Added production-grade observability via structured JSON logging with **request correlation IDs** and Docker healthcheck endpoints.

---

## Technical Skills

| Category | Technologies |
| :--- | :--- |
| **Languages** | JavaScript, TypeScript, C++, Java |
| **Backend** | Node.js, Express.js, REST APIs, JWT, Microservices |
| **Databases** | PostgreSQL, MongoDB, Redis, MySQL, Prisma ORM |
| **DevOps & Tools** | Docker, GitHub Actions, AWS S3, Jest, Supertest, Sentry, Git, Postman |

---

## Technical Writing

<table>
  <tr>
    <td width="50%">
      <a href="https://medium.com/@arnavkumargupta777/strong-consistency-in-distributed-systems-raft-algorithm-e366649ffb1e">
        <img width="100%" src="https://github.com/user-attachments/assets/d8eab445-0a9d-4151-b1c1-006fa5e97262" />
      </a>
      <br>
      <b><a href="https://medium.com/@arnavkumargupta777/strong-consistency-in-distributed-systems-raft-algorithm-e366649ffb1e">Strong Consistency: The Raft Algorithm</a></b>
      <br>
      <sub>A deep dive into leader election, log replication, and safety guarantees in distributed systems.</sub>
    </td>
    <td width="50%">
      <a href="https://medium.com/@arnavkumargupta777/merge-islands-game-design-and-analysis-of-algorithms-0303a537d78d">
        <img width="100%" src="https://github.com/user-attachments/assets/1871b9fe-e3dd-4339-ab82-7df57ac17256" />
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

## Education

**CHRIST (Deemed to be University), Bangalore** &nbsp;·&nbsp; B.Tech in Computer Science &nbsp;·&nbsp; `2023 – 2027` &nbsp;·&nbsp; **CGPA: 3.85 / 4**

`Data Structures` `Operating Systems` `OOP` `Computer Networks` `DBMS` `Cloud Computing` `Design & Analysis of Algorithms`
