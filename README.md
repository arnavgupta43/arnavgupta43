![MasterHead](https://user-images.githubusercontent.com/10498744/210012254-234538ff-d198-48aa-8964-37e6fd45d227.gif)
<h1 align="center">Hi 👋, I'm Arnav Kumar Gupta</h1>
<h3 align="center">Backend Developer & CS Student</h3>

<p align="center"> 
  <img src="https://komarev.com/ghpvc/?username=arnavgupta43&label=Profile%20views&color=0e75b6&style=flat" alt="arnavgupta43" /> 
</p>

## 🚀 About Me

I am a **Backend Engineering Intern** and 3rd-year CS student with a focus on **Scalable Backend Systems**. I don't just write code; I solve production-level problems like rate-limiting, payment integration, and high-concurrency systems.

* 🔭 **Currently working on:** Optimizing MCP API endpoints at Smallcase Technologies & Studying Low-Level Design.
* 🌱 **Deep diving into:** Distributed Systems (Raft Consensus) and Data Structures & Algorithms.

---

## 💼 Work Experience

### **Backend Engineering Intern - Smallcase Technologies**
*April 2026 – Present*

* Optimized **16 wealth-domain API endpoints** for the in-house AI assistant's MCP by stripping redundant fields and UI-only formatting, achieving a **30–45% token reduction** per endpoint.
* Saved approximately **~1.5M tokens platform-wide** and decreased API bandwidth, executing comprehensive end-to-end tests to guarantee zero feature degradation or loss of output quality.
* Monitored production health and resolved critical backend anomalies using **Sentry alerts**, debugging and patching live issues to maintain high API reliability and system uptime.

### **Software Engineering Intern - CodeWiser**
*January 2026 – February 2026*

* Contributed to backend development by integrating **Razorpay** for subscription-based plans, implementing webhook listeners to automate recurring billing and access control.
* Designed a **rate-limiting system** for LLM APIs using PostgreSQL row-level locking and transactional integrity, enforcing usage quotas at scale.
* Optimized application performance by refactoring **NextAuth session handling**, achieving a **100% reduction** in redundant user-fetch API calls during page navigation.

### **Software Engineering Intern - Gullak Money**
*April 2025 – May 2025*

* Reduced critical production defects through rigorous debugging and implementing dedicated unit tests.
* Owned the end-to-end implementation and deployment of a utility service, delivering ahead of schedule.

---

## ✨ Key Projects

### **1. MicroTasker — Event-Driven Task Management Backend**
*Stack: Node.js, Express, MongoDB, RabbitMQ, Docker, JWT*
* Designed an event-driven microservices architecture using **RabbitMQ** to publish and consume user and task domain events, enabling loose coupling and asynchronous workflows across services.
* Implemented a reliable notification service with durable queues, explicit message acknowledgments, and graceful shutdown handling (SIGTERM/SIGINT) to safely process in-flight events and prevent message loss.
* Added production-grade observability through structured JSON logging with request correlation IDs and health/readiness endpoints integrated into **Docker healthchecks**.

### **2. Flash-Sale Reservation Engine — High-Concurrency Inventory System**
*Stack: Node.js, Express, Redis (Lua), PostgreSQL, Redis Streams*
* Built a high-concurrency inventory reservation API utilizing optimistic Redis transactions **(WATCH/MULTI)** and TTL-based holds to prevent oversells.
* Designed an event-driven workflow with **Redis Streams** and a worker service to process hold lifecycle events (created, confirmed, cancelled, expired) and persist state in Postgres.
* Implemented idempotency safeguards and transactional database writes for safe retries, validating zero-oversell invariants via **k6 load testing** (100 VUs) that sustained **~1.6K RPS at p95 <35ms**.

---

## 🛠️ Technical Skills

| Category | Skills |
| :--- | :--- |
| **Languages** | JavaScript, C++, Java |
| **Backend** | Node.js, Express.js, REST APIs, JWT, Microservices |
| **Databases** | PostgreSQL, MySQL, MongoDB, Redis, Prisma ORM |
| **DevOps & Tools** | Docker, AWS (S3), GitHub Actions, Jest, Supertest, Git, Postman |

---

## ✍️ Technical Writing & System Design

I write about complex computer science topics to solidify my understanding.

<table>
  <tr>
    <td width="50%">
      <a href="https://medium.com/@arnavkumargupta777/strong-consistency-in-distributed-systems-raft-algorithm-e366649ffb1e">
        <img width="100%" src="https://github.com/user-attachments/assets/d8eab445-0a9d-4151-b1c1-006fa5e97262" />
      </a>
      <br>
      <strong><a href="https://medium.com/@arnavkumargupta777/strong-consistency-in-distributed-systems-raft-algorithm-e366649ffb1e">Strong Consistency: The Raft Algorithm</a></strong>
      <br>
      <p>A deep dive into providing strong consistency in distributed environments.</p>
    </td>
    <td width="50%">
      <a href="https://medium.com/@arnavkumargupta777/merge-islands-game-design-and-analysis-of-algorithms-0303a537d78d">
        <img width="100%" src="https://github.com/user-attachments/assets/1871b9fe-e3dd-4339-ab82-7df57ac17256" />
      </a>
      <br>
      <strong><a href="https://medium.com/@arnavkumargupta777/merge-islands-game-design-and-analysis-of-algorithms-0303a537d78d">Merge Islands: DSU Algorithm</a></strong>
      <br>
      <p>Designing a game using Disjoint Set Union with path compression.</p>
    </td>
  </tr>
</table>

---

<h2>📊 Coding Statistics</h2>

<div align="center">
  <br />

  <a href="https://leetcode.com/arnavgupta_43">
    <img src="https://leetcard.jacoblin.cool/arnavgupta_43?theme=dark&font=baloo&ext=heatmap" alt="Arnav's LeetCode Stats" />
  </a>

</div>

---

## 🎓 Education

**CHRIST (Deemed to be University)**, Bangalore
*B. Tech in Computer Science (2023 – 2027)* | **CGPA:** 3.85/4

**Key Coursework:** Data Structures, Operating Systems, OOP, Computer Networks, DBMS, Cloud Computing, Design and Analysis of Algorithms

---
