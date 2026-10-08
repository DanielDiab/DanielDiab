<div align="center">

# Hi, I'm Daniel 👋

### AI Engineer · Agents, RAG & Evaluation · Full-Stack Developer
**Systems and Computing Engineering @ Universidad de los Andes** · Bogotá, Colombia

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=2E8B57&center=true&vCenter=true&width=600&lines=Building+AI+agents+with+LangGraph+%2B+RAG;Authoring+MCP+servers+and+evaluation+gates;Shipping+full-stack+apps+end+to+end;1st+Place+Nationwide+%E2%80%94+IEEEXtreme+19.0)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-felipe-diab-gonzalez-427523347)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diabgonzalez9@gmail.com)

</div>

---

### 🧭 About me

I build **agentic AI systems and the machinery that makes them trustworthy** — evaluation gates, guardrails, traces and cost controls — and I ship them end to end, from the ingestion pipeline to the deployed agent talking to real users.

- 🔭 **Currently:** **Generative AI Research Monitor** at Uniandes, leading a connected AI-agent platform (LangGraph + n8n + Open WebUI) for internal university processes
- 🚢 **In production:** [SenecaReader](#-featured-projects) — an agentic RAG platform in active use by the Engineering Faculty
- 🔌 **Authored 6 MCP servers** and a three-layer evaluation gate in [Charter](#-featured-projects)
- 💼 **Freelance track record:** cut a client's LLM operating costs **25%** and built AI automations that lifted their sales **35%**
- 🏆 **1st place nationwide (Colombia)** — IEEEXtreme 19.0
- 👥 **President**, IEEE Computer Society Uniandes — grew the chapter to **70+ active members** and ran ~20 technical events
- 🎓 **Teaching Assistant**, Business Systems (SAP S/4HANA, Dolibarr ERP/CRM)
- 🌱 Currently going deeper on **AWS Bedrock**, agent evaluation and competitive programming

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

**Charter — Agent Platform with MCP & Eval Gate**

LLM agents declared as **versioned YAML manifests** (purpose, constraints, acceptance criteria) that must clear a three-layer evaluation gate before publishing: the agent's own suite against a risk-based threshold, shared security suites (direct + indirect prompt injection, cross-customer PII) at 100%, and cost/latency vs. budget.

Six MCP servers, input/output guards that verify every figure against tool results, span-based tracing, an OpenAI-compatible API, and an "Architect" agent that generates new agents from an interview. 85 offline tests.

`MCP` `LangGraph` `Python` `Evals` `Guardrails`

</td>
<td width="50%" valign="top">

**SenecaReader — Agentic RAG** · *in production*

Lets Universidad de los Andes' Engineering Faculty search decades of Council-meeting minutes in natural language.

Document-ingestion pipeline converting PDFs, OCR'd scans and DOCX into structured indexed JSON — recovering hyperlinks, repairing dropped accents that silently broke matching, extracting action items — plus a **resumable batch CLI** so a failure partway through hundreds of documents doesn't lose the run.

On top: a LangGraph agent with hybrid keyword + semantic retrieval, JWT auth and prompt-injection guardrails.

`RAG` `LangGraph` `OCR` `GCP` `JWT`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Stochastic](https://stochastic-beta.vercel.app) — Forecasting Platform**

Ingests real-time market data and runs ARIMA, Random Forest, RSI and MACD to generate forecasts. Currently integrating LLM-based reasoning so the output explains *why*, instead of returning an unexplained number.

`Python` `scikit-learn` `Time Series` `pandas`

</td>
<td width="50%" valign="top">

**[CHRO/MATIC](https://chro-matic.vercel.app) — Design System Generator**

Generates a complete design system — palettes, typography, accessible components — from a single brand color using the perceptual **OKLCH** color space. Exports tokens to 6 formats including Figma Tokens and Style Dictionary.

`React` `TypeScript` `Tailwind` `a11y`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**OptiCloud — Microservices on AWS**

Multi-service architecture inside an AWS VPC: a Kong API gateway on EC2 routing to independent services (NestJS, Spring Boot, Django, FastAPI), each containerized on its own instance, backed by RDS PostgreSQL, MongoDB and a Redis cache.

`AWS` `EC2` `RDS` `Docker` `Microservices`

</td>
<td width="50%" valign="top">

**[STEPINSIGHT](https://stepinsight.vercel.app) — Footprint Analysis**

Environmental footprint analysis tool with a JS/HTML/CSS frontend and a Python/Jupyter analysis pipeline, deployed to production.

`JavaScript` `Python` `Jupyter`

</td>
</tr>
</table>

---

### 🛠️ Tech stack

**AI, Agents & Evaluation**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Servers-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_%2F_Hybrid_Retrieval-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

<sub>Eval harnesses & publish gates · prompt-injection testing · input/output guards · span-based tracing · cost & latency budgets · spec-driven agent design</sub>

**ML & Deep Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Frontend & Backend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Data & Cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### 📜 Certifications

| | |
|---|---|
| **Anthropic** | Model Context Protocol: Advanced Topics · Introduction to MCP · Claude Code in Action · AI Fluency: Framework & Foundations · Claude 101 |
| **NVIDIA** | Fundamentals of Deep Learning · Rapid Application Development with LLMs |
| **AWS** | Cloud Practitioner Essentials |
| **Microsoft** | Design Multi-Agent Memory Architectures with Azure Cosmos DB · AI Fluency |
| **CU Boulder** | Databases for Data Scientists · Relational Database Design · SQL |

---

### 📊 GitHub stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=DanielDiab&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DanielDiab&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=DanielDiab&theme=tokyonight&hide_border=true" />
</p>

---

<div align="center">

**Open to AI/ML and full-stack roles — available from December 2026.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-felipe-diab-gonzalez-427523347)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diabgonzalez9@gmail.com)

</div>
