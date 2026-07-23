I build autonomous AI systems end-to-end. Right now all-in on [Propab](https://propabai.com).

---

## Propab

An autonomous scientific research system. The goal is to compress humanity's discovery timeline: research that runs continuously, at machine scale, instead of in human-paced cycles.

I've been building this for a year now, including 4-6x full rebuild after internal audit showed me the architecture was wrong. under the hood:)

- **Campaign orchestration.** A persistent loop engine. Orchestrator and subagents are the same agent class at different hierarchy levels, native tool calls, no hardcoded intent parsing.
- **Hypothesis trees, not flat search.** Every synthesis output anchors to a completed parent node, so the search space converges instead of sprawling.
- **Evidence binding.** Every claim traces to a content-addressed artifact. Fabricated citations get caught at write time, not review time.
- **Literature retrieval at scale.** Hybrid BM25 + dense retrieval over open scholarly corpora (OpenAlex, Semantic Scholar), running on self-hosted index infrastructure because managed vector DBs don't survive contact with this scale.
- **Sandboxed execution.** Hypotheses get verified by actually running code, not by asking an LLM if they sound right.

Open-sourcing components as they stabilize.

---

## Stack

- **Languages:** Python, TypeScript
- **AI systems:** multi-agent orchestration, RAG / hybrid retrieval, embeddings, sandboxed tool execution
- **Data:** PostgreSQL, pgvector, Redis
- **Backend & infra:** FastAPI, Node.js, Docker, Kubernetes, GCP, self-hosted dedicated servers
- **Frontend:** Next.js, React

---

## Before this

Co-founded **[Accenox](https://www.accenox.com/in)**, a B2B software company for global clients. Team of 8, 30+ production systems shipped. Paused it to go full-time on Propab.

ps: I also contribute to open source repos (if you're maintaining one, ping me!)

---

## Find me

X: [@iykshani](https://x.com/iykshani) · LinkedIn: [shani-singh1](https://www.linkedin.com/in/shani-singh1/) · [propabai.com](https://propabai.com)
