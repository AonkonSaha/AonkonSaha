<h1 align="center">Hi 👋, I'm Aonkon Saha</h1>
<h3 align="center">Software Engineer | Spring Boot & Distributed Systems Enthusiast</h3>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Welcome%20To%20My%20Profile&fontSize=40" width="100%"/>
</p>

---

## 🛠️ Featured Engineering Projects

<br />

### 1. 🚀 CodeShian Online Judge
> **Personal Project** | *A distributed, real-time code execution and evaluation system supporting competitive programming and automated contests.*

[![Live Platform](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.codeshian.com)
[![GitHub Repository](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AonkonSaha)

#### System Architecture Highlights
* **⚡ Isolated Sandbox Execution:** Executes untrusted user code inside a secure, containerized execution environment (Judge0 / Docker) with enforced memory and CPU limits.
* **📡 Real-Time Event Streaming:** Implemented WebSocket channels to stream per-testcase execution states (`Running` → `Accepted` / `TLE` / `WA`) to clients instantly, eliminating HTTP polling overhead.
* **🧠 Sub-Millisecond Caching Layer:** Leveraged Redis to cache high-frequency read data (problem sets, live contest leaderboards, user session states), significantly decreasing database read pressure under burst submission loads.
* **🔐 Enterprise Security & Auth:** Designed multi-tenant access control with JWT and Google OAuth 2.0 supporting role-based access control (`NORMAL_USER`, `PROBLEM_EDITOR`, `ADMIN`).
* **🎁 Gamified Mechanics:** Features an integrated reward ledger and daily login coin economy to drive active user retention.

#### Tech Stack
`Java` • `Spring Boot` • `React` • `WebSocket` • `Redis` • `PostgreSQL` • `MySQL` • `Docker` • `Tailwind CSS`

---

### 2. 📰 BWN News Portal
> **Client Project** | *A high-concurrency digital media platform engineered for rapid editorial publication, sub-second page delivery, and intelligent social crawler optimization.*

[![Live Website](https://img.shields.io/badge/Live_Website-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.bwnnews.com)

#### System Architecture Highlights
* **☁️ Edge-Based Crawler Optimization:** Deployed **Cloudflare Workers** at the network edge to intercept incoming traffic from social media crawlers (Facebook, WhatsApp, Twitter, Discord). Dynamically injects Open Graph meta tags and renders link previews instantly without hitting origin server rendering bottlenecks.
* **⚡ Content Management Pipeline:** Purpose-built administrative CMS optimized for low-latency media publishing and fast editorial workflows.
* **📈 High Traffic Resilience:** Structured database schema and query execution plans in PostgreSQL to ensure sustained uptime during breaking news traffic spikes.

#### Tech Stack
`Java` • `Spring Boot` • `React` • `Cloudflare Workers` • `PostgreSQL` • `Tailwind CSS`

---

## 💻 Technical Capabilities

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
</p>

---

## 📊 GitHub Performance

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AonkonSaha&show_icons=true&theme=radial" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AonkonSaha&layout=compact&theme=radial" width="48%" />
</p>

---

## 📫 Connect with Me

* 🌐 Platform: [codeshian.com](https://www.codeshian.com)
* 💼 LinkedIn: [linkedin.com/in/aonkonsaha](https://linkedin.com/in/aonkonsaha)
* 📧 Email: aonkonpustcse@gmail.com
