# Pranay Panakanti

**Backend engineer.** I build systems and then run them. Two are live right now.

[![Portfolio](https://img.shields.io/badge/Portfolio-0E64AF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://portfolio.prostriver.me/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranay-panakanti)
[![LeetCode](https://img.shields.io/badge/LeetCode%201722-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/GV2023005096/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:panakantipranay@gmail.com)

B.Tech CSE, 2027 · Backend and distributed systems · Open to internship and full-time roles

---

## 🚀 What I'm running

### [ProStriver](https://prostriver.me/) — study productivity platform
Live in production with **220+ users** at **99.93% uptime**. Java 21, Spring Boot, multi-module Maven.

- Moved 40–50 second Gemini LLM generation **off the request path** onto a Kafka pipeline on Confluent Cloud, cutting client response to a **253 ms acknowledgment**. One topic, two partitions, keyed ordering, idempotent consumers, dead-letter handling.
- Redis caching took endpoint latency from **342 ms to 90 ms** at a **92.5% hit ratio**.
- **Dual-cloud from one Docker image** — an AWS EC2 API node and a DigitalOcean scheduled-jobs node, switched by Spring profiles.
- **Polyglot persistence** — PostgreSQL for relational user and session data, MongoDB Atlas for LLM responses and study-plan workflows.
- Shipped a **RAG support assistant** into production on pgvector and Spring AI, grounding Gemini answers in retrieved chunks with enforced structured JSON output.
- Stateless JWT with rotating refresh tokens, RBAC, Bucket4j rate limiting. GitHub Actions CI/CD. Instrumented with Actuator, Micrometer, Prometheus and Grafana.

[**Backend repo →**](https://github.com/pranaypanakanti/ProStriver_Backend)

### [GITAM Aero Astro Club Platform](https://gitam-aero-astro-club.vercel.app/) — full-stack
The official club platform, serving **1,200+ students** at **99.78% uptime**.

- **40+ secure REST APIs** with JWT authentication and role-based access control.
- Automated recruitment workflows and email alerts, cutting manual admin effort by **70%**.
- React frontend built end to end by directing Claude Code as an agentic AI workflow.

[**Frontend →**](https://github.com/g-aeroastro-c/webapp) · [**Backend →**](https://github.com/pranaypanakanti/GITAM-AERO-ASTRO-CLUB)

---

## 🧰 Tech

**Core**
![Java](https://img.shields.io/badge/Java-%23ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-%236DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-%236DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

**Distributed systems and caching**
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031?style=for-the-badge&logo=redis&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**Cloud and delivery**
![AWS](https://img.shields.io/badge/AWS-%23FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff?style=for-the-badge&logo=digitalocean&logoColor=white)

**Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

**AI engineering**
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector%20RAG-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Also work with**
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/React-%2320232a?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Git](https://img.shields.io/badge/Git-%23F05033?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📌 Elsewhere

**Software Engineer Intern, Landmine Soft** — built 10+ REST APIs in Java and Spring Boot within a cross-functional team, took unit-test coverage to **87%** with JUnit, documented every endpoint with Swagger and OpenAPI.

**Vice President, AWS Cloud Club GITAM** — lead a 60+ member community, grew active participation 20% through AWS Jam sessions and peer-led builds.

**#1 overall**, Meta Developer Communities 5-round DSA series, GITAM chapter.
