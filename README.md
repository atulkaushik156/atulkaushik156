<h1 align="center">Atul Kaushik</h1>

<p align="center">
  <strong>Python Backend Engineering · Applied AI · Retrieval Systems</strong>
</p>

<p align="center">
  <a href="mailto:atulkaushik156@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Atul" />
  </a>
  <a href="https://www.linkedin.com/in/atul-kaushik-2a2605381/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Atul on LinkedIn" />
  </a>
  <a href="https://x.com/itsatulkaushik">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Atul on X" />
  </a>
  <a href="https://github.com/atulkaushik156">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Atul on GitHub" />
  </a>
</p>

I'm a second-year Computer Science student at **Maharaja Agrasen Institute of Technology (MAIT), Delhi**. Python is my strongest language, and I enjoy building backend systems and practical AI applications — especially the parts involving data handling, retrieval, validation, and reliability.

I'm currently looking for **Python backend, software engineering, or applied AI internships** where I can take ownership of real features and help ship useful software.

---

## Projects

### Sequelo — Multi-tenant AI analytics

**Ask questions about CSV data in plain English and get SQL-backed answers.**

<p align="center">
  <a href="https://sequelo.onrender.com/">
    <img src="https://img.shields.io/badge/Live%20demo-Visit%20Sequelo-2463EB?style=for-the-badge" alt="Open Sequelo live demo" />
  </a>
  <a href="https://github.com/atulkaushik156/sequelo">
    <img src="https://img.shields.io/badge/Source%20code-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Sequelo source code" />
  </a>
</p>

Sequelo lets users upload CSV files, review the inferred schema, and ask questions about their data. LangGraph workflows generate SQL, while deterministic checks validate queries before DuckDB executes them.

- Built the backend with **Python and FastAPI**, with a React/Vite frontend.
- Used **SQLGlot AST validation** to reject non-`SELECT` statements before execution.
- Added a bounded **Executor–Judge** loop to send failed queries for revision instead of retrying indefinitely.
- Added schema checks requiring at least **95% primary-key uniqueness** and **80% foreign-key matching**.
- Implemented Google OAuth 2.0/OIDC with PKCE, Redis-backed sessions, tenant-scoped upload paths, and Dockerized deployment on Render.

<p align="center">
  <a href="https://github.com/atulkaushik156/sequelo">
    <img src="https://raw.githubusercontent.com/atulkaushik156/sequelo/main/docs/5.png" alt="Sequelo chat interface" width="850" />
  </a>
</p>

### Offline Multimodal Document Assistant

**A local document-question-answering API for PDFs, images, and tables.**

[View source code](https://github.com/atulkaushik156/Offline-Multimodal-Rag-)

This project processes PDF text, scanned-page OCR content, images, and tables. It combines lexical and semantic retrieval to find relevant context before generating an answer with local Ollama models.

- Combined **BM25** lexical retrieval with **pgvector** semantic search.
- Used local Ollama models for embeddings, table processing, image understanding, and multimodal chat.
- Exposed document-ingestion and question-answering endpoints through FastAPI.
- Runs pgvector and Redis services with Docker Compose.

---

## Technologies

These are tools I've used across my projects. Python is my primary programming language; React and Vite were used for the Sequelo frontend.

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

**Backend, AI and retrieval**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-4B6BFB?style=for-the-badge" alt="LangGraph" />
  <img src="https://img.shields.io/badge/RAG-5B6472?style=for-the-badge" alt="Retrieval augmented generation" />
  <img src="https://img.shields.io/badge/BM25-5B6472?style=for-the-badge" alt="BM25" />
  <img src="https://img.shields.io/badge/Ollama-111111?style=for-the-badge" alt="Ollama" />
  <img src="https://img.shields.io/badge/SQLGlot-333333?style=for-the-badge" alt="SQLGlot" />
</p>

**Databases and infrastructure**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge" alt="pgvector" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

**Frontend used in Sequelo**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

---

## Contact

<p>
  <a href="mailto:atulkaushik156@gmail.com">
    <img height="38" src="https://img.shields.io/badge/Email%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Send me an email" />
  </a>
  <a href="https://www.linkedin.com/in/atul-kaushik-2a2605381/">
    <img height="38" src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" />
  </a>
  <a href="https://x.com/itsatulkaushik">
    <img height="38" src="https://img.shields.io/badge/Follow%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" />
  </a>
</p>

- **Email:** [atulkaushik156@gmail.com](mailto:atulkaushik156@gmail.com)
- **LinkedIn:** [linkedin.com/in/atul-kaushik-2a2605381](https://www.linkedin.com/in/atul-kaushik-2a2605381/)
- **X:** [@itsatulkaushik](https://x.com/itsatulkaushik)
