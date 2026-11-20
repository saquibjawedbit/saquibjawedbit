<h1 align="center">Hi, I'm Saquib 👋</h1>

<p align="center">
  <b>Software engineer: backend systems & AI agents</b><br/>
  Python · TypeScript · Bengaluru, India · CS @ BIT Mesra (CGPA 9.0)
</p>

<p align="center">
  <a href="https://linkedin.com/in/mdsaquibjawed"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://saquibjawedbit.github.io/"><img src="https://img.shields.io/badge/Portfolio-222?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/></a>
  <a href="https://blog.saquibjawedbit.live/"><img src="https://img.shields.io/badge/Blog-555?style=for-the-badge&logo=hashnode&logoColor=white" alt="Blog"/></a>
  <a href="https://codeforces.com/profile/saquibjawed"><img src="https://img.shields.io/badge/Codeforces-Specialist_1504-1f8acb?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
</p>

---

### 💼 Experience

**Adbrew** · Software Engineering Intern · *Sept 2026 – now (first stint Dec 2025 – Apr 2026)*
- Real-time Amazon Marketing Stream sync on SQS + autoscaling ECS workers (**100K+ events/day**), cutting data delay from **2–3 hours to seconds** for 2,000+ advertiser orgs
- Reporting on 250M-document MongoDB collections: a page load went from **35 s to 2 s**, and a core query got **2.7× faster with 75% fewer reads**

**Cisco, Cloud Security** · Software Engineering Intern · *May – Jul 2026 · return offer*
- Built **NovaAI**, an autonomous on-call agent on the Claude Agent SDK that investigates incidents, finds root causes and raises fix PRs, saving **2–3 on-call hours per incident**
- Extended DSPM to Snowflake and 5 vector databases, and built a DLP pipeline that flags PII in vector collections (**~60% fewer manual audits**)

**Ping Browser** · Software Engineering Intern · *Feb – Dec 2025*
- ML phishing detection that classifies pages inline in **under 50 ms**
- Moved logs to per-tenant OpenSearch: P95 query time **4 s → 800 ms**

**CivicVoice** · Co-founder · *2024 – 2025*
- Took an AI complaint-resolution platform from idea to **5 paying organisations**, with a LangGraph agent that triages, routes and escalates complaints

---

### 🌍 Open source

**A2A Protocol** · Linux Foundation · 26k stars · the agent-to-agent standard started by Google: Fixed three bugs in the Python SDK's v0.3 compatibility layer, the path older agents use to talk to new ones. The gRPC client ignored per-call timeouts, so a slow agent could hang a caller forever; push-notification deletes broke on IDs with special characters; and the JSON-RPC delete returned the wrong response shape. Each fix ships with a failing-first regression test. · [#1497](https://github.com/a2aproject/a2a-python/pull/1497) [#1486](https://github.com/a2aproject/a2a-python/pull/1486) [#1481](https://github.com/a2aproject/a2a-python/pull/1481)

**Pydantic** · 29k stars · Python's most widely used data validation library: Fixed schema generation so that an error partway through no longer leaves stale internal state behind and corrupts the next schema built in the same process. · [#13859](https://github.com/pydantic/pydantic/pull/13859)

**AWS Powertools for Lambda** · AWS's official toolkit for serverless Python: Stopped the Logger from silently turning string messages like `"123"` or `"true"` into numbers and booleans, and made the Parameters utility fall back safely instead of crashing every invocation on a malformed setting. · [#8838](https://github.com/aws-powertools/powertools-lambda-python/pull/8838) [#8839](https://github.com/aws-powertools/powertools-lambda-python/pull/8839)

**NVIDIA NeMo Agent Toolkit** · NVIDIA's framework for building and profiling AI agents: The MCP client read only the first page of tools from paginated servers and silently dropped the rest. Agents now see every tool the server offers. · [#2614](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2614)

**Microsoft PyRIT** · 5k stars · Microsoft's AI red-teaming framework: Fixed the SATA masking attack so words with accents and combining marks (Hindi, Vietnamese and more) are masked whole instead of being split mid-character. · [#4390](https://github.com/microsoft/PyRIT/pull/4390)

Also in review: fixes in **MLflow**, **Docling**, **LiveKit Agents** and **Microsoft Agent Governance Toolkit**.

---

### 🚀 Featured projects

| | |
|---|---|
| **[Mocklly](https://mocklii.intropi.in)**: AI voice interviewer on LiveKit, **500+ interviews** at ~500 ms latency, 10+ orgs on a multi-tenant AWS ECS backend | **[Deep Research Agent](https://github.com/saquibjawedbit/Deep-Research-Agent)**: multi-step web research reports in 5–10 minutes (CrewAI, FastAPI, Next.js) |
| **[Squook](https://github.com/saquibjawedbit/squook-faceless-Video-generator)**: prompt-to-video pipeline (CrewAI agents + Remotion renderer + React editor) | **[CivicVoice](https://github.com/saquibjawedbit/CivicVoice)**: civic reporting app with geotagged reports and an RBAC admin dashboard (Flutter) |
| **[Amazon ML Challenge](https://github.com/saquibjawedbit/amazon-ml-mvp)**: entity resolution with BGE embeddings + LightGBM, **ranked 70th of 8,000+ teams** | **[Founder Email Finder](https://saquibjawedbit.github.io/founder-email-finder/)**: free Apify tool to find a company founder's email from its website |

---

### 🏆 Achievements

- **Amazon ML Challenge:** 70th of 8,000+ teams (top 1%)
- **Competitive programming:** Codeforces Specialist (1504), LeetCode Knight (1860), 1,100+ problems solved
- **Amazon HackOn:** semi-finalist among 10,000+ teams
- **Hackathons:** won Hatch From Scratch and Hard Hack; regional winner, NXP AI in Mobility

---

### 🛠️ Tech

**Languages:** Python · TypeScript · JavaScript · Java · C++ · Dart · SQL<br/>
**Backend:** Django · FastAPI · NestJS · Express · Celery · BullMQ · Pydantic<br/>
**AI:** AI agents · RAG · LangChain · LangGraph · Claude Agent SDK · CrewAI · Agno · LiveKit<br/>
**Data & cloud:** MongoDB · Redis · OpenSearch · Snowflake · Pinecone · Qdrant · AWS (ECS, SQS, EC2) · Docker · Terraform<br/>
**Frontend & mobile:** React · Next.js · Flutter

---

### 📊 GitHub stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=saquibjawedbit&theme=tokyonight" alt="GitHub stats" height="160" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=saquibjawedbit&theme=tokyonight" alt="Most-used languages" height="160" />
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=saquibjawedbit&theme=tokyonight" alt="Contributions" width="90%" />
</p>
