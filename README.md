# Giordano Alvari

**Senior AI / ML Engineer** — I build LLM systems that survive contact with production.

Currently at **Enel**, where I design and deliver agentic-AI systems for IT&S control room
operations across Italy and Spain: tool-using diagnostic agents, multi-agent RAG, and LLM
orchestration wired into ServiceNow, network monitoring and device APIs.

Before LLMs I spent years on large-scale forecasting and churn modelling (18M contracts,
hierarchical forecasting with conformal prediction). Before that, computational biology at
DKFZ/EMBL — single-cell eQTL mapping, published in *Genome Biology*.

That mix is the point: I care as much about **proving a system works** as about building it.

---

### What I'm building

| | |
|---|---|
| **[RadixForge](https://github.com/gioalvari/radixforge)** | Radix-tree KV-cache orchestrator for multi-agent LLM inference on Apple Silicon. When 10 agents share a 2000-token system prompt, compute it once — zero-copy prefix sharing via native `llama.cpp` APIs. `C++17` |
| **[Agent Memory Layer](https://github.com/gioalvari/agent-memory-layer)** | Transparent OpenAI-compatible proxy that gives any agent persistent, searchable memory. Local Metal-accelerated embeddings, SQLite vector store, temporal-decay retrieval. Zero code changes in your agent. `C++17` |
| **[global-forecasting](https://github.com/gioalvari/global-forecasting)** | Train one model across many time series, with zero-shot forecasting support. `Python` |
| **[hybridforecast](https://github.com/Dhonveli/hybridforecast)** | Decompose a series, forecast each component, recombine — a harness for testing hybrid forecasting models fast. `Python` |

---

### Stack

`Python` `C++17` `SQL` · LlamaIndex · llama.cpp · PyTorch · FastAPI · Pydantic · PySpark · Ray · AWS (Bedrock) · Docker

---

### Elsewhere

[gioalvari.github.io](https://gioalvari.github.io) · [LinkedIn](https://www.linkedin.com/in/giordano-alvari-137b7b10a/) · [Genome Biology paper](https://doi.org/10.1186/s13059-021-02407-x) · giordano.alvari@gmail.com

*Based in Florence, Italy. Open to remote and hybrid roles.*
