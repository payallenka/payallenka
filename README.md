<h1 align="center">Hi, I'm Payal 👋</h1>

<p align="center"><b>AI & Full-Stack Engineer</b> — I build the hard parts of products.</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=8B87FF&center=true&vCenter=true&width=620&lines=AI+agents+%26+organisational+memory;Observability+%26+distributed+tracing;Open-source+fixes+in+Go+%26+Java;Developer+tools+on+npm" alt="what I build" />
</p>

<p align="center">
  <a href="https://payallenka.vercel.app"><img src="https://img.shields.io/badge/Portfolio-8B87FF?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/payallenka/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://dev.to/payallenka"><img src="https://img.shields.io/badge/DEV-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white"></a>
  <a href="https://medium.com/@payalm.lenka"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white"></a>
  <a href="https://substack.com/@ustuloabsque123904"><img src="https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white"></a>
  <a href="mailto:payalm.lenka@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

By day I'm a software engineer at **Codifinary (CodeXray)**, working on a production **observability platform**. The rest of the time I ship AI and product work for startups across the 🇬🇧 **UK**, 🇺🇸 **US**, and 🇦🇺 **Australia**, contribute fixes to **open-source infrastructure**, and publish small, sharp **developer tools**.

I like problems with real stakes — where **correctness, latency, and money** are on the line.

### 🔭 Currently
- 📊 **Traces, service maps & latency analytics at CodeXray** — per-service execution breakdowns, p90 latency, request/error counts · `Go` · `ClickHouse` · `React` · `OpenTelemetry`
- 🧠 **Organisational memory for an AI workspace** — versioned document memory, a context graph across MCP sources (Notion, Slack, GitHub, Gmail), Claude agents · `Qdrant` · `MCP` · `Langfuse`
- 🤖 **AI-driven PR pipelines** — Claude Code review and test-generation in CI across a dozen services
- 🌍 **Open-source fixes** in CNCF, Kubernetes, Red Hat and database ecosystems (below)

### 📦 Published on npm

| Package | What it does |
|---|---|
| **[safety-label](https://www.npmjs.com/package/safety-label)** · [repo](https://github.com/payallenka/safety-label) | Finds the tracker SDKs compiled into an Android APK/AAB and drafts Google Play **Data safety** answers from vendors' own disclosures. Offline, zero dependencies, scans a 191 MB APK in ~0.4 s; CI mode fails a build that adds a tracker. |
| **[npm-publish-doctor](https://www.npmjs.com/package/npm-publish-doctor)** · [repo](https://github.com/payallenka/npm-publish-doctor) | npm is retiring 2FA-bypass tokens. `npx npm-publish-doctor` reads your workflows and `package.json`, tells you what will break when you move to **trusted publishing (OIDC)**, and prints the exact `npm trust` commands. Read-only. |
| **[interceptor-engine](https://www.npmjs.com/package/interceptor-engine)** | Real-time API & LLM observability — patches `fetch` to capture latency, cost and prompts. |

Plus the **[Explain Code Simply](https://marketplace.visualstudio.com/items?itemName=payallenka.explain-code-simply)** VS Code extension — AI code explanations, right in the editor.

### 🌍 Open source

**Merged**
- **[Jaeger](https://github.com/jaegertracing/jaeger/pull/10049)** (CNCF) — cancel remote-storage trace streams when iteration stops early
- **[OpenTelemetry Collector Contrib](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/52761)** — Oracle DB receiver: check `rows.Err` and close rows
- **[Keycloak](https://github.com/keycloak/keycloak/pull/55327)** — keep a `$` that doesn't start a placeholder intact in `StringPropertyReplacer`
- **[Quarkus](https://github.com/quarkusio/quarkus/pulls?q=is%3Apr+author%3Apayallenka+is%3Amerged)** ×3 — [negated predicates in MongoDB Panache queries](https://github.com/quarkusio/quarkus/pull/58409) · [Dev Services JDBC timeout for MySQL/MariaDB/MSSQL](https://github.com/quarkusio/quarkus/pull/57990) · [stop propagating Gradle default values](https://github.com/quarkusio/quarkus/pull/58128)
- **[Debezium Spanner connector](https://github.com/debezium/debezium-connector-spanner/pull/180)** — don't mutate record headers in place when adding timestamps

**In review** — [ClickHouse Go](https://github.com/ClickHouse/clickhouse-go/pull/2091) · [MongoDB Go driver](https://github.com/mongodb/mongo-go-driver/pull/2714) · [Google ADK Go](https://github.com/google/adk-go/pull/2462) · [go-containerregistry](https://github.com/google/go-containerregistry/pull/2513) · [Kubernetes agent-sandbox](https://github.com/kubernetes-sigs/agent-sandbox/pull/2376) · [llm-d](https://github.com/llm-d/llm-d-router/pull/4402) · [Podman](https://github.com/podman-container-tools/podman/pull/30341) · [OpenEverest](https://github.com/openeverest/openeverest/pull/3659) · [Jaeger](https://github.com/jaegertracing/jaeger/pull/10259) · [OTel ClickHouse exporter](https://github.com/open-telemetry/opentelemetry-collector-contrib/pull/53435)

### 🛠️ Tech I build with

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=flat-square&logo=quarkus&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

### 🌟 Selected work

| Project | What it is |
|---|---|
| **[fde-order-intake-agent](https://github.com/payallenka/fde-order-intake-agent)** | Forward-deployed-engineering case study: taking an AI order-intake agent live inside a distributor's real systems — Odoo ERP, a reverse-engineered legacy stock tool, and a messy SFTP price list |
| **[TrackerLens](https://github.com/payallenka/trackerlens)** | Android app that shows which companies' tracking code is inside your apps and warns when an update adds more. On-device, no internet permission, GPL-3.0 |
| **[rollout](https://github.com/payallenka/rollout)** | Make a breaking change once — get pull requests opened on every repo that needs it |
| **[AgentHub](https://github.com/payallenka/AgentHub)** | Real-time collaborative AI dashboard — CRDT sync (Yjs), offline-first, Groq-backed model proxy |
| **[Unbox](https://github.com/payallenka/unbox)** | Interactive virtual gifts — blow out candles with your mic, pop balloons, break a wax seal. The whole gift lives in the link; no backend |
| **[Bookstore Microservices](https://github.com/payallenka/Microservices)** | Spring Boot + Spring Cloud: Eureka, Gateway, OpenFeign, per-service PostgreSQL with Flyway, one `docker compose up` |
| **[ScholarshipHub](https://github.com/payallenka/ScholarshipScraping)** | Scrapes 10 global scholarship sources into one schema; Llama 3.3 70B builds a personalised top-10 shortlist |

<details>
<summary><b>More things I've built</b></summary>

- **Obligo** — turns signed contracts into checks against real business data: an LLM extracts the obligation graph, a deterministic engine decides breach / at-risk / compliant with evidence
- **Orbit** — a durable, event-sourced runtime for AI agents in Go; crashed runs resume without repeating work
- **Runscan** — critical-path analysis for AI agent traces (OpenTelemetry, Langfuse, LangSmith): why a run was slow and where the money went, all in the browser
- **FlakeGuard** — CI reliability intelligence: ingest CI runs, rank flaky tests by engineer-hours lost
- **Jarvis Mobile** — personal assistant whose memory lives on your Android phone and whose thinking runs on any paired computer
- **GridMind** — AI operations prototype for data-centre power and cooling
- **Askly / Slotly** — SaaS MVPs: a cited, document-grounded business assistant, and multi-tenant booking for local businesses

</details>

### 📈 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=payallenka&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=payallenka&layout=compact&theme=tokyonight&hide_border=true" />
</p>

### 🏆 Highlights
- 💼 Software Developer @ **Codifinary (CodeXray)**
- 🌍 Merged contributions to **Jaeger, OpenTelemetry, Keycloak, Quarkus and Debezium**
- 📦 **3 npm packages** + a **VS Code extension**
- 📄 Research paper accepted at **ICWITE 2026**
- 👩‍💻 Ex **GDSC Core** · Ex **IEEE Student Chapter Chair**
- 🔬 Contributor to a **patent-backed** project
- 🧩 **250+ LeetCode** · **CodeChef 3★**

### 🌐 Let's build something
💬 **Open to freelance projects, collaborations, and genuinely hard problems.**

📫 **payalm.lenka@gmail.com**
🔗 Portfolio: **[payallenka.vercel.app](https://payallenka.vercel.app)** · Studio: [Lenkara](https://lenkara.vercel.app)
✍️ [DEV](https://dev.to/payallenka) · [Medium](https://medium.com/@payalm.lenka) · [Substack](https://substack.com/@ustuloabsque123904) · 💼 [LinkedIn](https://www.linkedin.com/in/payallenka/) · 🧩 [LeetCode](https://leetcode.com/payallenka)

---

<p align="center"><i>I'd rather ship one real thing than a hundred demos.</i></p>
