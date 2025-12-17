# Hi, I'm Daniele Celsa. 👋

### GenAI Engineer | Multi-Agent Systems Architect
**Based in Milan, Italy** 🇮🇹

I am a Telecommunications Engineer pivoting to **production-grade Generative AI**. I don't just write scripts that talk; I engineer resilient, observable, and cost-aware AI architectures. My work focuses on moving beyond simple chatbots to build autonomous systems using primarily **LangGraph**, the **Model Context Protocol (MCP)**, and **Agentic RAG**.

---

### 🛠️ Technical Proficiency

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

---

### 🏗️ Engineering Case Studies

#### 1. [Hierarchical Multi-Agent Orchestrator](https://orchestrator.46.224.88.247.nip.io/)
A **Supervisor-Worker** system that decomposes vague user requests into executable actions across Calendar, Email, and SQL agents.
*   **Architecture:** LangGraph State Machine with a Supervisor node.
*   **Key Feature:** Deterministic **SQL Schema Introspection** to eliminate hallucinations during entity resolution.
*   **Observability:** Custom Callback Handlers for real-time **Token Usage & USD Cost attribution** per-agent.

#### 2. [Decoupled Autonomous Researcher (MCP)](https://chat-w-search.46.224.88.247.nip.io/)
An implementation of the **Model Context Protocol (MCP)** standard to separate the LLM reasoning engine (Client) from tool execution (Server).
*   **Architecture:** Microservices pattern communicating via **Server-Sent Events (SSE)**.
*   **Key Feature:** **Hybrid Grounding** logic that validates AI summaries against raw search metadata to ensure citation accuracy.
*   **Stack:** FastMCP (Server) + Streamlit (Client).

#### 3. [Enterprise Document Intelligence](https://agentic-rag.46.224.88.247.nip.io/)
An **Agentic RAG** system that focuses on data privacy and decision-making over linear retrieval.
*   **Architecture:** Recursive retrieval loop with query rewriting.
*   **Key Feature:** **Session-Scoped Vector Stores** (Ephemeral ChromaDB) ensuring strict data isolation between user sessions.
*   **Logic:** The agent autonomously decides *if* retrieval is necessary or if the answer is in-context.

---

### 🚧 Currently Engineering (Work in Progress)

#### 4. Multimodal Compliance Auditor
*Status: In Development*

I am currently building an AI Auditor designed to ingest raw video and audio for automated risk assessment. This moves beyond text-only processing to handle long-context multimedia streams.

*   **Multimodal Ingestion:** Leveraging **Gemini 2.5** to process video and audio streams natively.
*   **Structured Output:** Utilizing **Pydantic** to force the LLM into strict JSON schemas for automated downstream processing.
*   **Goal:** To perform automated sentiment analysis and compliance scoring on recorded meetings.

---

### 📫 Connect with Me

*   **Portfolio & Demos:** [danielecelsa.github.io]([https://danielecelsa.github.io/portfolio/])
*   **LinkedIn:** [linkedin.com/in/danielecelsa]([https://www.linkedin.com/in/domenico-daniele-celsa-518b758b/])
*   **Email:** danielecelsa@gmail.com

<!--
**DanieleCelsa/DanieleCelsa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<!--
**danielecelsa/danielecelsa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
