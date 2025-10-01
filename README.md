<!--
  Hi! This profile README is designed to be clean, fast, and ATS-friendly.
  Keep sections tight; update the "Now" board monthly.
-->

<h1 align="center">Rahul Podugu</h1>
<p align="center">
  <b>Software Engineer — backend, distributed systems, and AI-assisted platforms</b><br/>
  Java • Spring Boot • Kafka • AWS • Redis • Kubernetes • LangChain • Vector Search
</p>

<p align="center">
  <a href="https://github.com/Rahul2251999"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-@Rahul2251999-181717?logo=github"></a>
  <a href="mailto:rahulpodugu2@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-rahulpodugu2%40gmail.com-0078D4?logo=microsoftoutlook&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/rahulpodugu/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-rahulpodugu-blue?logo=linkedin"></a>
</p>

<p align="center">
  <img alt="Focus" src="https://img.shields.io/badge/Focus-Event--driven%20payments%20%7C%20RAG%20for%20ops%20portals-0A0A0A">
  <img alt="Location" src="https://img.shields.io/badge/Location-USA-0A66C2">
  <img alt="Open To" src="https://img.shields.io/badge/Open%20to-Backend%20%7C%20Platform%20%7C%20Infra%20roles-067A46">
</p>

---

### Snapshot
- Built and shipped Spring Boot microservices on AWS handling **100K+ daily transactions** with **99.9% uptime**  
- Introduced **Kafka + Saga** patterns; cut service latency by **~40%**  
- Implemented a **RAG** customer-support layer with LangChain; automated **~30%** of payment queries  
- Vector search with **FAISS** improved answer accuracy by **~25%**  
- p99<sup>th</sup> **≤150 ms** for 50K+ users after systematic perf work (Redis, SQL tuning, autoscaling)

---

### What I’m building right now
- Turning payment workflows into **event-driven** streams with sane saga orchestration and idempotent consumers  
- Hardening an **AI incident copilot**: source-grounded steps, rollback plans, and selective fallbacks to keyword search  
- Pragmatic reliability work: **dashboards, budgets, SLOs,** and boring, repeatable release pipelines

---

### Selected Work

#### 🔐 SecureShare — Decentralized P2P File Sharing  
Hybrid **RSA + AES**, DHT indexing, and a multithreaded pipeline for 3× faster access vs. naive P2P.  
`Java` `Networking` `Crypto`  
➡️ Repo: https://github.com/Rahul2251999/Peer-to-Peer-Secured-File-System

#### ⚡ Real-time Stock Trading Engine  
Lock-free, CAS-driven matching with price-time priority and sub-ms tick processing across 1K+ symbols.  
`Java` `Concurrency` `Low-latency`  
➡️ Repo: https://github.com/Rahul2251999/stock-trading-engine

#### 🤖 AI-Powered Support Chatbot  
Azure Bot Services + custom NLP + RAG for payments documentation; ~60% better first-touch resolution.  
`LangChain` `Vector Search` `Azure`  
➡️ Repo: https://github.com/Rahul2251999/AI-Powered-Customer-Support-Chatbot

<details>
  <summary><b>Architecture notes (click to expand)</b></summary>

- **Eventing:** Kafka topics per domain aggregate; outbox + schema evolution; strict idempotency keys  
- **Sagas:** Choreography for simple flows, orchestration when cross-domain compensation is non-trivial  
- **Search:** Hybrid retrieval (BM25 + cosine) with FAISS IVF-HNSW for balanced recall/latency envelopes  
- **Safety:** Source-grounded steps with links; confidence gating to legacy results on low-score thresholds  
- **Perf:** Hot-path caching (Redis), deliberate N+1 audits, async boundaries, autoscaling on queue depth
</details>

---

### Tech I reach for
<p>
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white">
  <img alt="Spring" src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=spring&logoColor=white">
  <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-111?logo=python&logoColor=white">
  <img alt="FAISS" src="https://img.shields.io/badge/FAISS-0052CC">
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white">
  <img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white">
</p>

---

### Operating model
- **Build for failure first.** Idempotent handlers, retries with backoff, DLQs, and clear compensations  
- **Bias for clarity.** Small PRs, ADRs for irreversible choices, runbooks with decisive steps  
- **Measure, then move.** SLOs, budgets, and one-pager experiments before expensive migrations

---

### “Now” board
- [ ] Tighten saga compensations for partial captures  
- [ ] Add RAG evaluator with source-coverage and step-accuracy scoring  
- [ ] Move from single-region writers to multi-AZ quorum for a latency-sensitive service segment

---

### GitHub at a glance
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Rahul2251999&show_icons=true&hide_border=true" alt="Rahul's GitHub stats"/>
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=Rahul2251999&hide_border=true" alt="Rahul's GitHub streak"/>
</p>
<p align="center">
  <img height="140" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rahul2251999&layout=compact&hide_border=true" alt="Top languages"/>
</p>

---

### Connect
- 💼 LinkedIn: <a href="https://www.linkedin.com/in/rahulpodugu/">/in/rahulpodugu</a>  
- ✉️ Email: <a href="mailto:rahulpodugu2@gmail.com">rahulpodugu2@gmail.com</a>

<!-- Footnotes -->
<sub>Key metrics and highlights summarized from my recent resume.</sub>
