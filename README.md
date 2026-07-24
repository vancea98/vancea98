### Hi, I'm Mihai — pivoting from enterprise process automation into AI Engineering.

I spent 5 years building business-critical automation for the Renault Group
(Microsoft Power Platform, Dataverse, complex approval/governance workflows)
before deciding to go deep on the current generation of AI systems: RAG,
agentic architectures, and knowledge graphs. This profile is the evidence of
that transition — five projects, each with a real technical reason to exist,
not tutorial clones.

**Currently**: finishing an M.Sc. in Intelligent Systems, and pursuing
Microsoft's AI Engineer Associate certification (AI-103).

---

#### 🧠 [vaultmind](https://github.com/vancea98/vaultmind)
An Obsidian vault knowledge-graph explorer that surfaces "implicit
connections" — note pairs that share an LLM-extracted entity but were never
manually linked, something Obsidian's own graph view structurally can't do.
Includes a live model-switcher for swapping the local LLM per session. Three
real bugs found and fixed via live-testing, documented honestly rather than
hidden.

#### 🕸️ [neo4j-graphrag](https://github.com/vancea98/neo4j-graphrag)
A production-shaped Neo4j GraphRAG service — built specifically after a job
interview involving Neo4j GraphRAG didn't go well. Vector search + Cypher
graph traversal + GDS community detection, behind FastAPI and Docker
Compose. This is that gap, closed.

#### 📊 [rag-failure-bench](https://github.com/vancea98/rag-failure-bench)
Measures the "RAG has 5 classic failure modes" claim empirically against
SQuAD 2.0, instead of taking it on faith — quantified before/after deltas
per fix, not anecdotes.

#### 📘 [rag-playbook](https://github.com/vancea98/rag-playbook)
A modular, config-driven production RAG template covering the full current
technique set (contextual retrieval, late chunking, agentic RAG, GraphRAG,
multimodal) — 15 Architecture Decision Records documenting every non-obvious
design call.

#### 💬 [rag-chat](https://github.com/vancea98/rag-chat)
The deliberately simple baseline everything else in this portfolio is
measured against: plain retrieve → generate, no fixes, readable start to
finish in minutes.

---

All five run **100% locally** via [Ollama](https://ollama.com) — no API
keys, no cloud bill, clone and run.

Also building and selling productized automation: [MCP Packs](https://github.com/vancea98/mcp-packs-preview) (n8n + Claude Desktop bundles).

📫 mihaivancea1288@gmail.com · [LinkedIn](https://www.linkedin.com/in/vancea-mihai-catalin)
