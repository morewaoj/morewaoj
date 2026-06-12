# Oluwamorewa Omolabi
### AI Engineer · Product Builder · Atlanta, GA

CS graduate from Georgia State University building AI systems that solve real problems — not demos, not tutorials. Systems that are grounded, cited, evaluated, and deployed.

[![Portfolio](https://img.shields.io/badge/Portfolio-morewa.vercel.app-c9a55a?style=flat&logo=vercel&logoColor=white)](https://morewa.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-morewao-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/morewao/)

---

## What I Build

**AI & LLM Systems** — RAG pipelines, grounded generation, vector search, prompt engineering, agentic workflows

**Product Engineering** — full-stack platforms with real users, real data, and real deployment

**Data & Intelligence** — recommendation engines, hybrid matching systems, analytics pipelines

---

## Featured Projects

### 🧠 The Unofficial Career Guide — RAG System
Full end-to-end Retrieval-Augmented Generation pipeline built from scratch. Deliberate chunking strategy (1000 char chunks, 150 char overlap, recursive splitting) across 15 real documents producing 58 semantically coherent chunks. ChromaDB vector store with cosine similarity search. Grounded generation via Groq LLaMA 3.3 — system prompt enforces citations and refuses out-of-scope queries rather than hallucinating. Evaluated against 5 test questions with documented accuracy judgments and honest failure case.

`Python` `RAG` `ChromaDB` `LangChain` `Groq LLaMA 3.3` `Gradio` `sentence-transformers`

[→ View on GitHub](https://github.com/morewaoj/unofficial-career-guide)

---

### ♟ RS Chess Coach — Multi-System AI Coach
Chess coaching AI combining three separate systems into one grounded response. Stockfish 18 handles position calculation — the LLM never guesses moves. A RAG pipeline over 8 chess knowledge documents retrieves opening theory, tactical patterns, and endgame technique. The LLM synthesizes both into a structured coaching response with citations and a concrete 3-5 move plan. Game memory persists across every turn via a FEN-based board state tracker. FastAPI backend with a drag-and-drop HTML frontend showing legal move highlights and a BEST move indicator.

`Python` `RAG` `Stockfish 18` `FastAPI` `ChromaDB` `fastembed` `Groq LLaMA 3.3` `chess.py`

[→ View on GitHub](https://github.com/morewaoj/chess-coach)

---

### 🎓 RS EduNav — AI Educational Guidance Platform
Live production platform helping students navigate college, career, and scholarship decisions. Hybrid matching engine tuned on 76,000+ real resume patterns surfaces career matches, 36,000+ college profiles, and personalized scholarship recommendations from a resume upload. Real-time job market data, demand trends, and outlook by career. Built with Claude and OpenAI APIs. Live at rsedunav.com. Mobile app pending App Store review.

`TypeScript` `React` `Node.js` `PostgreSQL` `Anthropic Claude` `OpenAI` `Expo` `Drizzle ORM`

[→ View on GitHub](https://github.com/morewaoj/RSedunav) · [→ Live Site](https://rsedunav.com)

---

### FitFindr — Multi-Tool Thrift Shopping AI Agent
Thrift-shopping AI agent that interprets natural-language requests, searches mock secondhand listings, chooses a matching item, suggests an outfit from the user's wardrobe, and creates a final fit card. Built around a conditional planning loop so later tools only run when earlier steps succeed. Includes Groq-powered query interpretation with deterministic fallback parsing, session state management, graceful error handling, pytest coverage, and a Gradio UI.

`Python` `Groq` `Gradio` `Multi-Tool Agents` `Planning Loops` `pytest`

[→ View on GitHub](https://github.com/morewaoj/fitfindr)

---

## Education

**Georgia State University** — B.S. Computer Science · 3.9 GPA · 2023–2025

**Georgia Military College** — A.S. Mathematics · 2021–2022

---

## Skills

| AI & LLM | Data & Backend | Frontend & Mobile |
|----------|---------------|-------------------|
| RAG Pipelines | Python | React / TypeScript |
| Vector Databases | PostgreSQL | React Native / Expo |
| Prompt Engineering | Node.js / Express | Tailwind CSS |
| Groq / OpenAI / Claude | Apache Spark | Gradio |
| Agentic Workflows | FastAPI | HTML / CSS / JS |
| ChromaDB / Pinecone | SQL (Advanced) | Vite |

---

*Open to AI Engineer, Solutions Engineer, and AI Integration roles.*
*Building at the intersection of LLMs, real data, and real products.*
