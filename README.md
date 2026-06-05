<div align="center">

```
██████╗ ███████╗██████╗  █████╗ ██████╗ ███████╗██╗  ██╗██╗
██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔══██╗██╔════╝██║  ██║██║
██║  ██║█████╗  ██████╔╝███████║██████╔╝███████╗███████║██║
██║  ██║██╔══╝  ██╔══██╗██╔══██║██╔══██╗╚════██║██╔══██║██║
██████╔╝███████╗██████╔╝██║  ██║██║  ██║███████║██║  ██║██║
╚═════╝ ╚══════╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝
```

**GenAI Engineer · Distributed Systems Builder · Mechanistic Interpretability Enthusiast**

*Building systems where agents think, collaborate, and explain themselves.*

[![Portfolio](https://img.shields.io/badge/Portfolio-debarshi29.github.io-0f0f0f?style=for-the-badge&logo=githubpages&logoColor=white)](https://debarshi29.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-debarshi29-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debarshi29)
[![IEEE](https://img.shields.io/badge/IEEE-Published-00629B?style=for-the-badge&logo=ieee&logoColor=white)](https://doi.org/10.1109/WCONF64849.2025.11233239)
[![Email](https://img.shields.io/badge/Email-debarshi2933@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:debarshi2933@gmail.com)

</div>

---

## `whoami`

```python
debarshi = {
    "role"        : "Incoming GenAI Engineer @ EY LLP",
    "education"   : "M.Sc. Big Data Analytics — RKMVERI",
    "location"    : "India",
    "building"    : ["multi-agent systems", "LLM infrastructure", "agentic workflows"],
    "researching" : ["mechanistic interpretability", "GNN theory", "hypergraph learning"],
    "obsessed_with": "the gap between what neural networks do and *why* they do it",
    "philosophy"  : "0% or 100%. Nothing in between.",
}
```

---

## ⚡ What I'm Working On

| Project | Stack | Status |
|---|---|---|
| **THGNN-MaGNet** — GNN + 6-agent LangGraph pipeline on NIFTY 500 | PyTorch · LangGraph · FinBERT · Streamlit | 🔬 Active |
| **A2A Multi-Agent Retail AI** — orchestrator + MCP tool servers + Redis memory | LangGraph · pgvector · Langfuse · AKS | ✅ Production |
| **Mech Interp Roadmap** — TransformerLens, SAEs, ARENA curriculum | Python · TransformerLens · Neel Nanda exercises | 📖 Ongoing |
| **DeepSeek / Lab Interview Prep** — Anthropic, OpenAI, DeepMind problem banks | Jupyter · PyTorch | 🧠 Long game |

---

## 🏗️ Tech Arsenal

<div align="center">

**Core Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**AI / ML / GenAI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Semantic Kernel](https://img.shields.io/badge/Semantic_Kernel-5C2D91?style=flat-square&logo=microsoft&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Cloud / Infra**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Data Engineering**

![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</div>

---

## 🔬 Selected Projects

### 🧠 [THGNN-MaGNet: Graph-Structured DL + Multi-Agent Decision Pipeline](https://github.com/debarshi29)
> *Temporal-Causal Hypergraph Neural Network meets a 6-agent LangGraph orchestration layer*

- Proposed **THGNN-MaGNet**: BiGRU MAGE encoder + Sparse MoE routing + Temporal-Causal Hypergraph (TCH) + Global Probabilistic Hypergraph (GPH), trained end-to-end with a differentiable Spearman IC loss on the **NIFTY 500 universe**
- **Rank-IC: 0.0398** (+95% over baseline) · **ICIR: 0.420** · **Annualised Sharpe: 3.71** over 583-day holdout
- Six-agent pipeline: GNN inference → FinBERT sentiment → portfolio fusion → risk profiler → macro regime → LLM report (Gemma-4-31b) — end-to-end in ~47s

`PyTorch` `LangGraph` `FinBERT` `Streamlit` `Hypergraph Learning`

---

### ⛓️ [Real-Time (T+0) Trade Settlement — IEEE Published](https://doi.org/10.1109/WCONF64849.2025.11233239)
> *Blockchain-native settlement with agentic pre-trade compliance*

- 4-node **Hyperledger Besu** IBFT-2 consensus network for deterministic finality **< 2 seconds**
- **LangGraph state machines** (Llama 3.2) for pre-trade compliance checks
- XGBoost fraud detection off-chain + SHAP/LIME explainability layer → **91.7% counterparty risk reduction**
- Published in **IEEE WCONF 2025**

`Hyperledger Besu` `LangGraph` `XGBoost` `XAI` `IBFT-2`

---

### 🤖 [NET-LINK: Self-Healing Drone Swarms (MARL)](https://github.com/debarshi29/Deep-Reinforcement-Learning-DA346/tree/main/DRL_Final%20Project)
> *5 agents learn to maintain communication relays — no handoff rules programmed*

- **MAPPO**-based multi-agent RL in a Gymnasium 3D airspace with physics/energy constraints
- Emergent relay-passing coordination within ~1,200 training episodes
- Agents independently developed coverage zone handoffs as peer energy depleted

`MAPPO` `MARL` `PyTorch` `Gymnasium` `Deep RL`

---

### ⚡ [Distributed LLM Inference Engine](https://github.com/debarshi29/Distributed-Large-Language-Models)
> *2–4× throughput on DeepSeek R1 and Llama 3.2B via model parallelism*

- Tensor + pipeline parallelism with CUDA kernels overlapping inter-node communication
- C++ core with Python bindings; larger models hit the upper 4× range

`C++` `CUDA` `Python` `Tensor Parallelism` `DeepSeek`

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=debarshi29&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=debarshi29&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)

[![GitHub Streak](https://streak-stats.demolab.com?user=debarshi29&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)](https://git.io/streak-stats)

</div>

---

## 🎯 What I'm Learning

```
2026 ROADMAP
├── 📜 Certifications
│   ├── Databricks Data Engineer Associate       [Q3 2026]
│   ├── Databricks Data Engineer Professional    [Q4 2026]
│   └── Azure DP-203 / AI-102                    [Q4 2026]
│
├── 🔬 Research Track
│   ├── TransformerLens + Neel Nanda 200 exercises
│   ├── ARENA curriculum (SAEs, activation patching)
│   ├── Circuits & Superposition literature
│   └── Mech interp on GNNs (largely open problem — my angle)
│
└── 🏗️ Engineering Track
    ├── Delta Lake / Medallion Architecture
    ├── dbt + Databricks Workflows + Unity Catalog
    └── Semantic Kernel deep dive @ EY
```

---

## 📄 Publication

> **Real-Time Trade Settlement for the US Market using Blockchain and AI**
> *IEEE WCONF 2025 — 3rd World Conference on Communication & Computing*
> DOI: [10.1109/WCONF64849.2025.11233239](https://doi.org/10.1109/WCONF64849.2025.11233239)

---

<div align="center">

**`System Online.`**

*If you're working on interpretability, multi-agent systems, or just want to talk about ideas — reach out.*

[![Portfolio](https://img.shields.io/badge/→_debarshi29.github.io-0f0f0f?style=for-the-badge)](https://debarshi29.github.io)

</div>
