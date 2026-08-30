# Giordano Alvari

**Senior AI / ML Engineer** — production LLM agents, forecasting, and the engineering between a prototype and a dependable system.

Currently at **Enel**, where I design and deliver agentic-AI systems for IT&S control room
operations across Italy and Spain: tool-using diagnostic agents, multi-agent RAG, and LLM
orchestration wired into ServiceNow, network monitoring and device APIs.

Before LLMs I spent years on large-scale forecasting and churn modelling (18M contracts,
hierarchical forecasting with conformal prediction). Before that, computational biology at
DKFZ/EMBL — single-cell eQTL mapping, published in *Genome Biology*.

I have owned programmes from business framing and architecture through production delivery,
led teams of up to five, and worked directly with executive stakeholders. That mix is the point:
I care as much about **proving a system works** as about building it.

### Selected impact

- Expanded an enterprise incident platform to cover approximately **90% of group IT incidents**, with approximately **5% closing autonomously**.
- Led production churn and claim modelling across **18M contracts**, delivering a **15% churn reduction and EUR 2.2M annual savings**.
- Built a forecasting programme from zero to production with a **team of five**, hierarchical models and calibrated uncertainty.

---

### What I'm building

| | |
|---|---|
| **[RadixForge](https://github.com/gioalvari/radixforge)** | Radix-tree KV-cache orchestrator for multi-agent LLM inference on Apple Silicon. When 10 agents share a 2000-token system prompt, compute it once — zero-copy prefix sharing via native `llama.cpp` APIs. `C++17` |
| **[Agent Memory Layer](https://github.com/gioalvari/agent-memory-layer)** | Transparent OpenAI-compatible proxy that gives any agent persistent, searchable memory. 37 unit/integration tests; batch embeddings benchmarked at up to 11x throughput on Apple Silicon. `C++17` |
| **[global-forecasting](https://github.com/gioalvari/global-forecasting)** | Train one model across many time series, with zero-shot forecasting support. `Python` |
| **[hybridforecast](https://github.com/Dhonveli/hybridforecast)** | Decompose a series, forecast each component, recombine — a harness for testing hybrid forecasting models fast. `Python` |

---

### Stack

`Python` `C++17` `SQL` · LlamaIndex · LangChain · llama.cpp · PyTorch · FastAPI · Pydantic · PySpark · AWS Bedrock · Kubernetes · Docker

---

### Elsewhere

[gioalvari.github.io](https://gioalvari.github.io) · [LinkedIn](https://www.linkedin.com/in/giordano-alvari-137b7b10a/) · [Genome Biology paper](https://doi.org/10.1186/s13059-021-02407-x) · giordano.alvari@gmail.com

*Based in Florence, Italy. Open to Senior and Lead AI/ML Engineering roles, remote across Europe or hybrid in Florence.*
