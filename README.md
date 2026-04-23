# Shani Singh

Founder-turned-engineer. I love building Ai agents and systems that are challenging.

---

## About

I build end-to-end AI systems - from raw data ingestion to deployed inference. Previously co-founded Accenox (B2B software, $30K+ revenue, 8 months) and built Propab AI (autonomous research agent: 20K+ papers indexed, 200-tool agent, 15x ingestion throughput via GPU parallelism). Currently finishing my CS degree while sharpening AI engineering skills.
---
## Stack

| Layer | Tools |
|---|---|
| **Languages** | Python, TypeScript, JavaScript |
| **AI & ML** | LLM orchestration, RAG, multi-agent systems, vector embeddings, CNN, LSTM, fine-tuning, transformers |
| **Databases** | PostgreSQL, pgvector, Supabase, Redis, MongoDB |
| **Backend** | FastAPI, Node.js, REST API design, distributed systems, microservices, message queues, system design |
| **Infra & DevOps** | Docker, Kubernetes, GCP (Cloud Run, GKE), CI/CD, Linux, Git |
| **Frontend** | React, Next.js |


---

## Projects

### [Propab AI](https://propabai.com) · [[Demo]](https://drive.google.com/file/d/1yeqzbm6w2B6c8bVFUkic6MsI6M0JDqQQ/view?usp=sharing) · *paused*

Autonomous scientific research agent built from scratch.

- Ingested, chunked, and embedded **20,000+ arXiv papers** into a pgvector (Supabase) vector store
- **15x throughput improvement** on corpus indexing via GPU-parallelised batch embedding
- **200-tool computational agent** with Docker-sandboxed Python execution — autonomously runs experiments, verifies hypotheses, emits structured outputs
- Hierarchical **scout + solver multi-agent architecture** deployed on GCP/Kubernetes
- Production RAG pipeline with cross-encoder re-ranking and context compression; <100ms retrieval via pgvector ANN indexing

`Python` `LLM orchestration` `RAG` `pgvector` `Supabase` `multi-agent` `Docker` `Kubernetes` `GCP`

---

### [Sentient — Road Infrastructure Risk Ranking](https://github.com/shani-singh1/sentient) · *BITS Pilani Capstone*

Deep learning pipeline for spatiotemporal infrastructure risk scoring.

- **CNN + LSTM** architecture on Sentinel-1 SAR satellite imagery and environmental stress signals
- **Self-supervised + weakly supervised** training regime to handle real-world label scarcity — no fully annotated ground truth required
- End-to-end system: satellite data ingestion → preprocessing → spatiotemporal feature encoding → risk scoring → FastAPI inference backend → React frontend with PostGIS schema and containerised deployment

`Python` `PyTorch` `CNN` `LSTM` `satellite imagery` `FastAPI` `PostGIS` `Docker Compose`

---

### [Accenox](https://www.accenox.com/in) · *paused*

B2B software company building production systems for global clients.

- **10+ production-grade systems** shipped across fintech, logistics, and e-commerce verticals
- **$30K+ revenue within 8 months**, serving clients across the US and Singapore
- Recruited and directed a cross-functional team of 8 across engineering, design, and delivery
- Full ownership: system architecture → sprint execution → client handoff

`Node.js` `React` `Next.js` `PostgreSQL` `Redis` `TypeScript`

---


## By the numbers

| | |
|---|---|
| 20,000+ | arXiv papers indexed and embedded |
| 15x | throughput gain on corpus ingestion (GPU parallelism) |
| 200 | tools built into the Propab computational agent |
| 10+ | production systems shipped at Accenox |
| <100ms | RAG retrieval latency via pgvector ANN indexing |

---

## Find me

- X: [@shani_singh1](https://x.com/shani_singh1)
- LinkedIn: [shani-singh1](https://www.linkedin.com/in/shani-singh1/)
- Propab: [propabai.com](https://propabai.com)

---

*Most production code lives on private company repos (client work under NDA, company GitHub orgs). Public work: Sentient (above). Propab components being open-sourced progressively.*
