# 👋 Hi, I'm Bruno Aragão Vivan

**AI Product Builder | Systems Orchestrator | Technical Product Leader**  
I drive products end-to-end — from discovery to production — using AI agents (Google AntiGravity + Claude) as a multiplier for design and execution. This lets me focus on product architecture, logic flows, and business modeling, delegating syntax, tests, and iteration to the agents.
> ⚡ **Power-User of Antigravity & Claude:** I don't passively copy AI output. I actively direct, constrain, and review LLMs — enforcing deterministic constraints, security boundaries, and clean codebases — to ship end-to-end validated products.

---

## 🛠️ Tech Stack & Tooling

### AI & Agentic Engineering
<p align="left">
  <img src="https://img.shields.io/badge/CrewAI-F15A24?style=for-the-badge" alt="CrewAI" />
  <img src="https://img.shields.io/badge/ScrapeGraphAI-4F46E5?style=for-the-badge" alt="ScrapeGraphAI" />
  <img src="https://img.shields.io/badge/MCP-0052FF?style=for-the-badge&logo=google&logoColor=white" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Gemini_API-8E75C2?style=for-the-badge&logo=google-gemini&logoColor=white" alt="Gemini API" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-009688?style=for-the-badge" alt="Prompt Engineering" />
</p>

### Languages & Frameworks
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
</p>

### Infrastructure & Databases
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/n8n-FF6C37?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=black" alt="Supabase" />
</p>

---

## ⚡ Builder Philosophy

*   **Multi-Agent & Graph Workflows:** Designing and deploying collaborative crews using **CrewAI** and intelligent, self-healing scraping pipelines via **ScrapeGraphAI**.
*   **High-Velocity Execution:** I build functional prototypes quickly, shifting rapidly from architectural design to solid deployments.
*   **Creative Problem Solving:** Out-of-the-box system integration and API orchestration to solve complex B2B workflow bottlenecks.
*   **Critical AI Collaboration:** I don't passively copy AI outputs. I actively challenge and guide LLMs, enforcing deterministic constraints, context compression, security boundaries, and clean codebases.
*   **Structured Process Design:** Code is only as good as its maintainability. I build modular toolchains with robust test coverage.

---

## 🚀 Key Projects & Portfolios

*   **[GARGALO](https://github.com/aragaobruno/gargalo-showcase) (Process Mining with Costs in R$ and Cited AI Answers)**  
    *[Live Demo](https://gargalo.onrender.com/demo) | Reads a process event log (ERP export or spreadsheet) entirely in the browser, maps the real flow, ranks bottlenecks by cost in R$ with their probable cause (resource, weekday, case attribute), and replays history under "what-if" scenarios. The LLM receives only aggregated metrics with anonymized names and must cite the metric behind every number; a client-side verifier flags anything that doesn't match. 3/3 planted bottlenecks found with the right cause across 5 seeds; no false causes on a negative control.*  
    `TypeScript` `Next.js` `In-browser analytics` `Groq / Ollama` `Vitest` `Docker`

*   **[GLOSA](https://github.com/aragaobruno/glosa-showcase) (Contract × Invoice Auditor with Verifiable AI)**  
    *[Live Demo](https://glosa-4tap.onrender.com/demo) | Reads a services contract (PDF), checks every line of every invoice and returns overcharges with the clause, the math and the amount to recover — readjustments against official Central Bank indices, SLA credits, cancelled items, duplicates. The LLM only proposes terms; a citation verifier blocks anything not literally in the PDF, and a deterministic engine does the money math. 56/56 planted errors found, 29/29 contract terms extracted correctly in production.*  
    `Next.js` `TypeScript` `Groq / Ollama` `Supabase` `Vitest` `Docker` `Fail-closed AI`

*   **[andaluz](https://github.com/aragaobruno/andaluz) (Agent Reliability Kernel)**  
    *A reference architecture and working MVP demonstrating durable state execution, Human-in-the-Loop (HITL) Temporal pausing, and FinOps real-time token costing for LLM agents in regulated production.*  
    `Temporal` `LiteLLM` `Python` `Docker` `FinOps`

*   **[Escudo Família](https://github.com/aragaobruno/escudo-familia) (Live PWA App & Anti-Fraud Protocol)**  
    *[Live Demo](https://aragaobruno.github.io/escudo-familia/) | A privacy-first, zero-server Progressive Web App (PWA) built to protect vulnerable family members against real-time AI voice-cloning and urgent financial scams.*  
    `PWA` `TypeScript` `React` `Zero-Server Architecture` `Security`

*   **[ai-video-factory](https://github.com/aragaobruno/ai-video-factory) (Local AI Video Generator)**  
    *A local multi-agent automated short video generator designed to optimize GPU/VRAM scheduling on consumer-grade hardware (6GB RTX 4050) running sequential LLM, TTS, SD, and Whisper models orchestrated via CrewAI.*  
    `CrewAI` `FastAPI` `Vite` `ComfyUI API` `Kokoro TTS` `MoviePy`

*   **[defensa-ai-architecture](https://github.com/aragaobruno/defensa-ai-architecture) (Case Study & Design Patterns)**  
    *A detailed system architecture showcase explaining security boundaries, local PII sanitization for LGPD compliance, and multi-agent queue processing in a legal-tech SaaS.*  
    `System Design` `Mermaid Diagrams` `LGPD Compliance` `ADRs`

*   **[brazilian-legal-calculators](https://github.com/aragaobruno/brazilian-legal-calculators) (LEP Regime Progression Engine)**  
    *A portable, zero-dependency TypeScript library for calculating prison regime progression and sentencing calculations under Brazilian Criminal Execution Law (LEP).*  
    `TypeScript` `Jest` `Package` `LEP`

*   **[toolbelt](https://github.com/aragaobruno/toolbelt) (AI Agent Skills & Toolchain)**  
    *A collection of context-compactors, smart git PR generators, and automated test bootstrappers designed to optimize LLM interactions and agent workflows. Backed by automated Jest/pytest unit tests and continuous integration.*  
    `Python` `Node.js` `GitHub Actions` `Jest` `pytest`

*   **[Engineering New Beginnings](https://github.com/aragaobruno/engineering-new-beginnings) (Tech Memoir)**  
    *A developer's blueprint on life engineering, transitioning from corporate burnout to building automated, self-sustaining micro-SaaS and lifestyle projects.*  
    `Markdown` `PDF Compilation` `Gemini Translation Pipeline`

*   **MindGuard AI (Private Repo)**  
    *An enterprise-grade CBT cognitive resilience app designed for high-stress engineering and corporate environments.*  
    `React` `Express` `Gemini API` `Supabase`

---

## 📬 Connect With Me

*   **Email:** [aragaobruno@gmail.com](mailto:aragaobruno@gmail.com)
- **LinkedIn:** [linkedin.com/in/bruno-aragao-vivan](https://www.linkedin.com/in/bruno-aragao-vivan/)

