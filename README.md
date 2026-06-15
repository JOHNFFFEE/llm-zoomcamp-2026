# My LLM Zoomcamp Journey

[![Course](https://img.shields.io/badge/LLM%20Zoomcamp-2026-blue)](https://github.com/DataTalksClub/llm-zoomcamp)
[![Status](https://img.shields.io/badge/Status-In%20Progress-green)]()
[![Slack](https://img.shields.io/badge/Community-Slack-purple)](https://datatalks.club/slack.html)

> My personal repository following the LLM Zoomcamp – building production-ready LLM applications with RAG, agents, vector search, and more.

---

##  About Me

I'm a ML Practitioner passionate about building practical AI applications. This repo documents my journey through the LLM Zoomcamp, including:

-  Homework submissions
-  Capstone project code
-  Notes and key takeaways
-  Custom implementations and experiments

---

## Course Progress

| Module | Topic | Status | Code | Notes |
|--------|-------|--------|------|-------|
| 1 | Agentic RAG |  Completed | [Link](./01-agentic-rag/) | [Notes](./notes/module1.md) |
| 2 | Vector Search |  Completed | [Link](./02-vector-search/) | [Notes](./notes/module2.md) |
| 3 | Orchestration |  In Progress | [Link](./03-orchestration/) | [Notes](./notes/module3.md) |
| 4 | Evaluation |  Pending | - | - |
| 5 | Monitoring |  Pending | - | - |
| 6 | Best Practices |  Pending | - | - |
| 7 | End-to-End Project |  Pending | - | - |
| Capstone | Final Project |  Planned | - | - |

---

##  Capstone Project

### [Project Name – Coming Soon]

**Problem:** [Brief description of what you're solving]

**Approach:**
- RAG pipeline with [vector database choice]
- [LLM model] for generation
- Evaluation using [metrics/method]

**Repo:** [Link to project repository]

---

##  Key Learnings

###  Architecture Patterns
- Building RAG pipelines from scratch
- Implementing hybrid search (vector + keyword)
- Agentic workflows with function calling

###  Tools & Technologies
| Category | Tools |
|----------|-------|
| Vector Search | minsearch, PGVector, Qdrant |
| Orchestration | Kestra |
| Evaluation | RAGAS, custom metrics |
| Monitoring | Prometheus, Grafana |
| Frameworks | LangChain, LlamaIndex |

###  Insights
1. [Key insight #1 about RAG or LLMs]
2. [Key insight #2 about evaluation]
3. [Key insight #3 about production deployment]

---

##  Repository Structure
├── 01-agentic-rag/ # Module 1: Basic RAG + agents
├── 02-vector-search/ # Module 2: Embeddings & vector DBs
├── 03-orchestration/ # Module 3: Kestra pipelines
├── 04-evaluation/ # Module 4: RAG evaluation
├── 05-monitoring/ # Module 5: Dashboards & observability
├── 06-best-practices/ # Module 6: Hybrid search, reranking
├── 07-project-example/ # Module 7: Complete example
├── capstone/ # My final project
├── notes/ # Personal study notes
├── homework/ # Homework solutions
└── experiments/ # Sandbox for trying ideas


---

##  Setup & Running

```bash
# Clone this repo
git clone https://github.com/YOUR_USERNAME/llm-zoomcamp-my-work.git
cd llm-zoomcamp-my-work

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows

# Install dependencies
pip install -r requirements.txt

# Set up API keys (OpenAI, etc.)
cp .env.example .env
# Edit .env with your keys


 My Progress Log
Week 1-2: Agentic RAG
Built basic RAG pipeline

Added function calling for tool use

Homework score: [X/100]

Week 3-4: Vector Search
Implemented semantic search with embeddings

Compared minsearch vs PGVector

Homework score: [X/100]

Week 5-6: Orchestration & Evaluation
Built Kestra workflows for data ingestion

Set up RAGAS evaluation framework

[More details...]

 Connect With Me
GitHub: @yourusername

LinkedIn: Your Name

X / Twitter: @yourhandle

Slack: @yourusername on DataTalks.Club

Acknowledgments
Alexey Grigorev and the DataTalks.Club team

Will Russell and Timur Kamaliev for the excellent content

Fellow learners in the #course-llm-zoomcamp Slack channel

License
This repository contains my personal work from the LLM Zoomcamp. Course materials belong to DataTalks.Club. My code and notes are shared for learning purposes.

⭐ Star this repo if you find it helpful – and good luck with your LLM journey!


---

## Quick Customization Tips

Replace the bracketed placeholders with your actual info:

| Placeholder | Replace with |
|-------------|--------------|
| `[Software Engineer / ...]` | Your actual role |
| `[Project Name]` | Your capstone project name |
| `[Brief description]` | What problem your project solves |
| `[Vector database choice]` | e.g., Qdrant, Pinecone, PGVector |
| `[LLM model]` | e.g., GPT-4o, Claude, Llama 3 |
| `[X/100]` | Your actual homework scores |
| `@yourusername` | Your GitHub/LinkedIn/Twitter handle |

This README shows you're an active practitioner who documents learning, builds projects, and engages with the community – exactly what employers and collaborators look for. 
