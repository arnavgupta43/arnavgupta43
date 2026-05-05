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

**Backend Engineering Intern — [Smallcase](https://smallcase.com)** &nbsp;`Apr 2026 – Present`

- Led the end-to-end architecture and development of a core segment deletion feature, owning the complete lifecycle from HLD and LLD through implementation, dev testing, and successful production delivery.
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

**Backend Development**
&nbsp; APIs, auth, business logic, and scalable services.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

<br>

**Databases & Infra**
&nbsp; Data modeling, persistence, and deployment-ready workflows.

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-232F3E?style=for-the-badge&logo=amazons3&logoColor=white)

<br>

**Tools**
&nbsp; Daily workflow tools for shipping, debugging, and iteration.

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

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
