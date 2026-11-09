# Atul Kaushik

![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=900&color=2F855A&center=true&vCenter=true&width=680&height=32&lines=Python+Backend+Development;Applied+AI+and+RAG+Systems;Building+and+Shipping+Software)

[LinkedIn](https://www.linkedin.com/in/atul-kaushik-2a2605381/) · [Email](mailto:atulkaushik156@gmail.com) · [GitHub](https://github.com/atulkaushik156)

## About

I'm a second-year Computer Science student at Maharaja Agrasen Institute of Technology, Delhi (first-year CGPA: 9.45/10). Python is my main language, and most of my work is around backend development and practical AI applications.

I like working on the parts that make software dependable: validating inputs, keeping data separated, handling failures, and making a project usable outside my own machine. I'm currently looking for internships in Python backend engineering, software engineering, or applied AI.

## Projects

### [Sequelo — Multi-tenant AI analytics](https://github.com/atulkaushik156/sequelo)

[Live demo](https://sequelo.onrender.com/) · [Source code](https://github.com/atulkaushik156/sequelo)

Sequelo lets users upload CSV files and ask questions about their data in plain English. LangGraph workflows turn those questions into SQL-backed answers, while deterministic checks handle query validation and execution.

- Built the API with **Python and FastAPI**, with a React/Vite interface.
- Used **SQLGlot AST validation** to reject non-`SELECT` statements before execution.
- Added a bounded **Executor–Judge** loop to route failed queries for revision instead of retrying indefinitely.
- Added schema-inference checks requiring at least **95% primary-key uniqueness** and **80% foreign-key matching**.
- Implemented Google OAuth 2.0/OIDC with PKCE, Redis-backed sessions, tenant-scoped upload paths, and Dockerized deployment on Render.

![Sequelo chat interface showing a natural-language question over CSV data](https://raw.githubusercontent.com/atulkaushik156/sequelo/main/docs/5.png)

**Built with:** Python, FastAPI, LangGraph, LangChain, SQLGlot, DuckDB, PostgreSQL, pgvector, Redis, Docker, React, and Vite.

### [Offline Multimodal Document Assistant](https://github.com/atulkaushik156/Offline-Multimodal-Rag-)

A local document-question-answering API for PDFs. It processes text, scanned-page OCR content, images, and tables, then retrieves relevant information using a combination of lexical and semantic search.

- Combined **BM25** retrieval with **pgvector** semantic search.
- Used local **Ollama** models for embeddings, table processing, image understanding, and multimodal chat.
- Exposed document-ingestion and question-answering endpoints through FastAPI.
- Runs the supporting pgvector and Redis services with Docker Compose.

**Built with:** Python, FastAPI, BM25, pgvector, Redis, Ollama, and Docker Compose.

## Tools I use

| Area | Tools and technologies |
| --- | --- |
| Languages | **Python**, C++, SQL |
| Backend | FastAPI, REST APIs |
| AI and retrieval | LangGraph, LangChain, RAG, BM25, embeddings, pgvector, Ollama |
| Databases | PostgreSQL, DuckDB, Redis |
| Engineering and deployment | Docker, Docker Compose, Git, GitHub, SQLGlot, OAuth 2.0/OIDC |
| Frontend exposure | React and Vite (used in Sequelo) |

## Get in touch

- **LinkedIn:** [linkedin.com/in/atul-kaushik-2a2605381](https://www.linkedin.com/in/atul-kaushik-2a2605381/)
- **Email:** [atulkaushik156@gmail.com](mailto:atulkaushik156@gmail.com)

---

![Animated view of my GitHub contribution graph](https://raw.githubusercontent.com/atulkaushik156/atulkaushik156/output/github-contribution-grid-snake.svg)
