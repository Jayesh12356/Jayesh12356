<!-- HERO BANNER -->
<div align="center">

<a href="https://github.com/Jayesh12356">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:4F46E5,100:7C3AED&height=230&section=header&text=Jayesh%20Koli&fontSize=64&fontColor=ffffff&fontAlignY=38&desc=Enterprise%20GenAI%20Engineer%20%E2%80%A2%20Backend%20Systems%20%E2%80%A2%20AI%20Governance&descAlignY=62&descSize=18&animation=fadeIn" alt="Jayesh Koli — Enterprise GenAI Engineer, Backend Systems, AI Governance" />
</a>

<!-- ANIMATED ROLE TAGLINE -->
<a href="https://github.com/Jayesh12356">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=900&color=8B5CF6&center=true&vCenter=true&width=820&lines=Enterprise+GenAI+Engineer;RAG+%26+Retrieval+Architect;LLM+Ops%2C+Evaluation+%26+Governance;Backend+Systems+Engineer;10%2C000%2B+Users+in+Production" alt="Roles" />
</a>

<!-- LIVE PORTFOLIO CTA -->
<p>
  <a href="https://portfoliovercel-ebon.vercel.app/" target="_blank" rel="noopener noreferrer">
    <img alt="Explore My Live Portfolio" height="46"
         src="https://img.shields.io/badge/%E2%96%B8_LIVE-EXPLORE_MY_PORTFOLIO_%E2%86%97-7C3AED?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0F172A" />
  </a>
  <br/>
  <sub><i>Interactive site &middot; Next.js &middot; GSAP &middot; Three.js &middot; Framer Motion</i></sub>
</p>

<!-- IDENTITY STRIP -->
<p>
  <img src="https://komarev.com/ghpvc/?username=Jayesh12356&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Jayesh12356?style=for-the-badge&color=4F46E5&labelColor=0F172A&label=FOLLOWERS" alt="Followers" />
  <img src="https://img.shields.io/github/stars/Jayesh12356?style=for-the-badge&color=06B6D4&labelColor=0F172A&label=STARS" alt="Stars" />
  <img src="https://img.shields.io/badge/Panvel%2C%20Navi%20Mumbai%2C%20IN-0F172A?style=for-the-badge&logo=googlemaps&logoColor=8B5CF6&label=BASED" alt="Based in Panvel, Navi Mumbai, India" />
</p>

<a href="https://portfoliovercel-ebon.vercel.app/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Portfolio" />
</a>
<a href="https://linkedin.com/in/jayesh-koli-042357227">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:jkoli6704@gmail.com">
  <img src="https://img.shields.io/badge/Email-D44638?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://github.com/Jayesh12356">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

---

## About

Enterprise GenAI Engineer with **4+ years** designing and shipping production-grade LLM systems for regulated enterprise workflows. I work where retrieval quality, structured outputs, governance, and cost control matter — building systems that pass finance, procurement, and compliance review without losing engineering rigor.

> **Currently** building production GenAI at **Jio Platforms (Reliance)** — LLM-assisted financial decision workflows with deterministic fallbacks, RAG over policy documents with role-based access controls, and a centralized LLM evaluation/governance framework with prompt versioning, drift detection, hallucination guards, and rollback. Pursuing **M.Tech, Software Systems at BITS Pilani (WILP)**.

---

## Impact in Numbers

<table>
  <tr>
    <td align="center" width="33%">
      <h2>10,000+</h2>
      <sub><b>Employees Served</b><br/>across enterprise platforms</sub>
    </td>
    <td align="center" width="33%">
      <h2>4+ yrs</h2>
      <sub><b>Production Experience</b><br/>backend &amp; GenAI systems</sub>
    </td>
    <td align="center" width="33%">
      <h2>30%</h2>
      <sub><b>Faster Response Times</b><br/>via architectural &amp; perf wins</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <h2>25%</h2>
      <sub><b>Workflow Efficiency Gain</b><br/>LLM-assisted decision flows</sub>
    </td>
    <td align="center">
      <h2>20%</h2>
      <sub><b>Procurement Cycle Cut</b><br/>scalable financial platform</sub>
    </td>
    <td align="center">
      <h2>35%</h2>
      <sub><b>Lower Latency</b><br/>event-driven services &amp; dashboards</sub>
    </td>
  </tr>
</table>

---

## Enterprise GenAI Capabilities

- **Decision Support** — LLM-powered systems with deterministic fallbacks, confidence-based routing, and human approval workflows for compliance-sensitive use cases.
- **RAG & Retrieval** — Retrieval-Augmented Generation pipelines over enterprise data with hybrid retrieval (BM25 + dense vectors), reranking, and strict role-based access controls.
- **Structured I/O & Streaming** — JSON-mode and Pydantic schemas plus SSE token streaming, so model output can flow safely into downstream backend systems and real-time approval consoles.
- **Evaluation & Governance** — Offline regression suites, LLM-as-a-Judge scoring, drift and hallucination detection, prompt and configuration versioning, and rollback strategies.
- **Event-Driven Integration** — GenAI services wired into event-driven backends with retries, circuit isolation, semantic caching, rate limiting, and trace-level observability.
- **Cloud-Native Guardrails** — Audit logging, PII redaction, jailbreak and topic-boundary defense, and granular cost and token-budget enforcement.

---

## Architecture Snapshot

```mermaid
flowchart LR
    User["Enterprise User"] --> Guard["Input Guardrails<br/>PII / Jailbreak / Topic"]
    Guard --> Router{"Confidence<br/>Router"}
    Router -->|"High"| Retr["Hybrid Retrieval<br/>BM25 + pgvector"]
    Router -->|"Low"| HITL["Human-in-the-Loop<br/>Approval Console"]
    Retr --> Rerank["Reranker<br/>Cohere / BGE"]
    Rerank --> LLM["LLM Call<br/>GPT-4o / Claude"]
    LLM --> Struct["Structured Output<br/>Pydantic + SSE"]
    Struct --> HITL
    Struct --> Audit[("Trace + Audit Log<br/>LangSmith-style")]
    HITL --> SAP["SAP / Approval System"]
```

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,2,30&height=2&section=header" alt="" />
</div>

## Tech Matrix

**GenAI &amp; LLM Engineering**

![OpenAI GPT-4o](https://img.shields.io/badge/OpenAI%20GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic Claude](https://img.shields.io/badge/Anthropic%20Claude-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-7C3AED?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere-39594D?style=for-the-badge&logo=cohere&logoColor=white)
![Embeddings](https://img.shields.io/badge/Embeddings-1E3A8A?style=for-the-badge&logoColor=white)
![Function Calling](https://img.shields.io/badge/Function%20Calling-4338CA?style=for-the-badge&logoColor=white)
![JSON Mode](https://img.shields.io/badge/JSON%20Mode-0E7490?style=for-the-badge&logoColor=white)
![SSE Streaming](https://img.shields.io/badge/SSE%20Streaming-7C3AED?style=for-the-badge&logoColor=white)

**RAG &amp; Retrieval**

![Hybrid Search](https://img.shields.io/badge/Hybrid%20Search-0F766E?style=for-the-badge&logoColor=white)
![BM25](https://img.shields.io/badge/BM25-0E7490?style=for-the-badge&logoColor=white)
![Reranking](https://img.shields.io/badge/Reranking-1E40AF?style=for-the-badge&logoColor=white)
![HyDE](https://img.shields.io/badge/HyDE-1A5C4E?style=for-the-badge&logoColor=white)
![Semantic Caching](https://img.shields.io/badge/Semantic%20Caching-0891B2?style=for-the-badge&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-2F6792?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-6B4FA0?style=for-the-badge&logo=qdrant&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-1A7A5E?style=for-the-badge&logo=milvus&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-1565A0?style=for-the-badge&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-111827?style=for-the-badge&logo=pinecone&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-22C55E?style=for-the-badge&logo=weaviate&logoColor=white)

**LLM Ops &amp; Governance**

![LangSmith](https://img.shields.io/badge/LangSmith-1A5C4E?style=for-the-badge&logo=langchain&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0F172A?style=for-the-badge&logoColor=white)
![Guardrails.ai](https://img.shields.io/badge/Guardrails.ai-7C3AED?style=for-the-badge&logoColor=white)
![NeMo Guardrails](https://img.shields.io/badge/NeMo%20Guardrails-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Prompt Versioning](https://img.shields.io/badge/Prompt%20Versioning-4338CA?style=for-the-badge&logoColor=white)
![LLM-as-a-Judge](https://img.shields.io/badge/LLM--as--a--Judge-1E3A8A?style=for-the-badge&logoColor=white)
![PII Redaction](https://img.shields.io/badge/PII%20Redaction-B71C1C?style=for-the-badge&logoColor=white)

**AI Frameworks &amp; Agents**

![LangChain](https://img.shields.io/badge/LangChain-2E6B5E?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1A5C4E?style=for-the-badge&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7B3FA0?style=for-the-badge&logo=llama&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-C0392B?style=for-the-badge&logo=crewai&logoColor=white)
![AutoGen](https://img.shields.io/badge/AutoGen-1565C0?style=for-the-badge&logo=microsoft&logoColor=white)
![DSPy](https://img.shields.io/badge/DSPy-2C3E7A?style=for-the-badge&logo=python&logoColor=white)

**Backend &amp; Systems**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-059669?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-2E7D32?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-555555?style=for-the-badge&logo=express&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![REST / OpenAPI](https://img.shields.io/badge/REST%20%2F%20OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white)

**Data &amp; Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2F6792?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-1A5C2E?style=for-the-badge&logo=mongodb&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-B71C1C?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-B71C1C?style=for-the-badge&logo=redis&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-0E7490?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-444444?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-1E40AF?style=for-the-badge&logo=typescript&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-5A3E8A?style=for-the-badge&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-0E7490?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Infra &amp; Engineering Practices**

![Docker](https://img.shields.io/badge/Docker-1565C0?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-444444?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-2E7D6E?style=for-the-badge&logo=render&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-5A3E8A?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![RBAC](https://img.shields.io/badge/RBAC-1A237E?style=for-the-badge&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-444444?style=for-the-badge&logo=githubactions&logoColor=white)
![SAP](https://img.shields.io/badge/SAP%20Integrations-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![Frappe](https://img.shields.io/badge/Frappe-0089FF?style=for-the-badge&logo=frappe&logoColor=white)

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Enterprise Financial Policy Assistant
**RAG · Hybrid Search · Human-in-the-Loop**

LLM-assisted financial analysis grounded in internal policy documents, with role-based document retrieval and structured prompt templates that constrain responses to approved enterprise sources.

- Hybrid search (**BM25 + dense vectors over pgvector**) with a reranking stage
- Recursive + semantic chunking tuned for adversarial finance queries
- Pydantic-validated JSON streamed to the approval console via **SSE**
- Confidence-based routing with full audit trails of prompts, context, outputs, and decisions

`FastAPI` `Python` `pgvector` `Redis` `LangChain` `OpenAI`

> **Impact** — sub-second perceived latency on long answers, full auditability for compliance-critical decisions.

</td>
<td width="50%" valign="top">

### LLM Evaluation, Monitoring &amp; Governance Framework
**Prompt Versioning · LLM-as-a-Judge · Trace Observability**

Centralized framework for testing, monitoring, and governing LLM behavior across enterprise applications — treating GenAI behavior as code with traceable changes and rollback capability.

- Automated quality scoring via **LLM-as-a-Judge** rubrics + heuristic checks
- Detection for hallucinations, retrieval failures, and behavioral drift
- End-to-end spans across **prompt → retrieval → generation → output**
- Semantic caching and per-tenant token budgets for cost control

`Python` `FastAPI` `LangSmith / Langfuse-style` `Redis` `PostgreSQL`

> **Impact** — post-hoc replay and root-cause analysis on failed runs, enforced cost and reliability constraints.

</td>
</tr>
</table>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,2,30&height=2&section=header" alt="" />
</div>

## GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Jayesh12356&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0F172A&title_color=8B5CF6&icon_color=06B6D4&text_color=E2E8F0&ring_color=8B5CF6" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jayesh12356&layout=compact&theme=tokyonight&hide_border=true&bg_color=0F172A&title_color=8B5CF6&text_color=E2E8F0&langs_count=10" alt="Top languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Jayesh12356&theme=tokyonight&hide_border=true&background=0F172A&stroke=8B5CF6&ring=06B6D4&fire=8B5CF6&currStreakLabel=8B5CF6" alt="GitHub streak" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=Jayesh12356&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="Trophies" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Jayesh12356&bg_color=0F172A&color=E2E8F0&line=8B5CF6&point=06B6D4&area=true&hide_border=true" alt="Contribution activity graph" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Jayesh12356/Jayesh12356/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Jayesh12356/Jayesh12356/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contributions snake animation" src="https://raw.githubusercontent.com/Jayesh12356/Jayesh12356/output/github-contribution-grid-snake-dark.svg" />
</picture>

<br/><br/>

<img src="./metrics.svg" alt="Auto-generated GitHub metrics" />

</div>

---

## Education

<sub>Top-percentile academic record across postgraduate, undergraduate, and school. Currently pursuing <b>M.Tech in Software Systems</b> at <b>BITS Pilani (WILP)</b>.</sub>

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/POSTGRADUATE-7C3AED?style=for-the-badge&labelColor=0F172A" alt="Postgraduate" />
      <h2>8.1<sub>&nbsp;/ 10</sub></h2>
      <b>M.Tech &middot; Software Systems</b><br/>
      <sub>BITS Pilani &mdash; WILP</sub><br/>
      <sub><i>2022 &mdash; 2026</i></sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/UNDERGRADUATE-4F46E5?style=for-the-badge&labelColor=0F172A" alt="Undergraduate" />
      <h2>9.0<sub>&nbsp;/ 10</sub></h2>
      <b>B.Sc. &middot; Computer Science</b><br/>
      <sub>Pillai College (Autonomous)</sub><br/>
      <sub><i>2019 &mdash; 2022</i></sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/HSC%20%C2%B7%20SCIENCE-06B6D4?style=for-the-badge&labelColor=0F172A" alt="Higher Secondary Science" />
      <h2>90<sub>%</sub></h2>
      <b>CBSE &middot; Higher Secondary</b><br/>
      <sub>Kendriya Vidyalaya Jr. College</sub><br/>
      <sub><i>2017 &mdash; 2019</i></sub>
    </td>
    <td align="center" width="25%">
      <img src="https://img.shields.io/badge/SSC%20%C2%B7%20CBSE-22C55E?style=for-the-badge&labelColor=0F172A" alt="Secondary School CBSE" />
      <h2>92.8<sub>%</sub></h2>
      <b>CBSE &middot; Class 10</b><br/>
      <sub>Datta Meghe World Academy</sub><br/>
      <sub><i>2016 &mdash; 2017</i></sub>
    </td>
  </tr>
</table>

---

## Connect

<div align="center">

<a href="https://portfoliovercel-ebon.vercel.app/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Live%20Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Portfolio" />
</a>
<a href="https://linkedin.com/in/jayesh-koli-042357227">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:jkoli6704@gmail.com">
  <img src="https://img.shields.io/badge/jkoli6704%40gmail.com-D44638?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://github.com/Jayesh12356">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="tel:+919372468778">
  <img src="https://img.shields.io/badge/%2B91%2093724%2068778-22C55E?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Phone" />
</a>

<br/><br/>

<sub><b>Reliability-first · Audit-first · Production-first.</b></sub>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:4F46E5,100:0F172A&height=120&section=footer&animation=fadeIn" alt="" />

</div>
