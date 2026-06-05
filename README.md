<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=14&duration=2000&pause=500&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=false&width=620&height=100&lines=const+debarshi+%3D+new+Engineer%28%29%3B;debarshi.focus+%3D+%5B+%22multi-agent+systems%22%2C+%22mech+interp%22%2C+%22distributed+systems%22+%5D;debarshi.question+%3D+%22what+do+neural+networks+do+—+and+why%3F%22" alt="intro" />
</div>

<br/>

<div align="center">

[![](https://img.shields.io/badge/-portfolio-0d1117?style=flat-square&logo=Firefox&logoColor=58a6ff)](https://debarshi29.github.io)&nbsp;
[![](https://img.shields.io/badge/-linkedin-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://linkedin.com/in/debarshi29)&nbsp;
[![](https://img.shields.io/badge/-IEEE_paper-0d1117?style=flat-square&logo=ieee&logoColor=58a6ff)](https://doi.org/10.1109/WCONF64849.2025.11233239)&nbsp;
[![](https://img.shields.io/badge/-mail-0d1117?style=flat-square&logo=gmail&logoColor=58a6ff)](mailto:debarshi2933@gmail.com)&nbsp;
[![](https://img.shields.io/badge/-@dc__2933-0d1117?style=flat-square&logo=x&logoColor=58a6ff)](https://x.com/dc_2933)

</div>

<br/>

---

<table width="100%"><tr><td width="50%" valign="top">

### about

M.Sc. Big Data Analytics @ RKMVERI

building systems where agents think, collaborate, and explain themselves — and then asking why they think what they think

currently obsessed with mechanistic interpretability on graph-structured models, a problem that is largely unsolved

</td><td width="50%" valign="top">

### stack

```
languages   python · java · rust · sql
agents      langgraph · langchain · semantic kernel
            langfuse · pgvector · qdrant · mcp
ml          pytorch · sklearn · xgboost · shap
cloud       azure · databricks · kubernetes
            docker · redis · mlflow
data        pyspark · polars · pandas · dbt
            delta lake · unity catalog
research    transformerlens · huggingface
```

</td></tr></table>

---

### selected work

<br/>

```
 ███████████████████████████████████████████████  THGNN-MaGNet
```

hypergraph GNN + 6-agent decision pipeline · NIFTY 500

| metric | value |
|:--|:--|
| rank-IC improvement | **+95%** over baseline |
| ICIR | **0.420** |
| annualised Sharpe | **3.71** |
| holdout | 583 days |
| end-to-end inference | ~47 seconds |

BiGRU MAGE encoder → Sparse MoE routing → Temporal-Causal Hypergraph + Global Probabilistic Hypergraph, trained jointly with a differentiable Spearman IC loss on the full NIFTY 500 universe. Six LangGraph agents share a typed state dict: GNN inference · FinBERT sentiment · portfolio fusion (α-weighted) · systematic risk profiler · macro regime · Gemma-4-31b research note.

`PyTorch` `LangGraph` `FinBERT` `Hypergraph Learning` `Streamlit`

<br/>

```
 ███████████████████████████████████████████████  T+0 Trade Settlement  ·  IEEE WCONF 2025
```

blockchain-native settlement with agentic pre-trade compliance · [↗ doi](https://doi.org/10.1109/WCONF64849.2025.11233239)

| metric | value |
|:--|:--|
| settlement finality | **< 2 seconds** |
| counterparty risk reduction | **91.7%** |
| consensus | IBFT-2 BFT |
| network | 4-node Hyperledger Besu |

LangGraph state machines (Llama 3.2) for pre-trade compliance. XGBoost scores every trade off-chain before it touches the ledger — SHAP and LIME surface the explainability layer on top.

`Hyperledger Besu` `LangGraph` `XGBoost` `XAI` `IBFT-2`

<br/>

```
 ███████████████████████████████████████████████  Distributed LLM Inference
```

tensor + pipeline parallelism · DeepSeek R1 + Llama 3.2B · [↗](https://github.com/debarshi29/Distributed-Large-Language-Models)

| metric | value |
|:--|:--|
| throughput gain | **2–4×** over single-GPU baseline |
| parallelism | tensor + pipeline |
| kernel strategy | CUDA comms overlapped with compute |

`Rust` `CUDA` `Python` `Distributed Systems`

<br/>

```
 ███████████████████████████████████████████████  NET-LINK  ·  MARL
```

self-healing drone swarms · emergent coordination · [↗](https://github.com/debarshi29/Deep-Reinforcement-Learning-DA346/tree/main/DRL_Final%20Project)

| metric | value |
|:--|:--|
| agents | **5** (shared critic, decentralized exec) |
| emergent coordination | **~1,200 episodes** |
| handoff rules programmed | **0** |

MAPPO. Agents independently learned to pass coverage zones as peers hit energy thresholds. No rule was written for this — it emerged.

`MAPPO` `MARL` `PyTorch` `Gymnasium`

---

### research track

```
mechanistic interpretability
  ├── TransformerLens + Neel Nanda 200 exercises
  ├── ARENA curriculum · SAEs · activation patching · circuits
  └── mech interp on GNNs  ←  largely open problem · my angle

engineering certifications
  ├── Databricks Data Engineer Associate   Q3 2026
  └── Databricks Professional + Azure AI-102   Q4 2026
```

---

### contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/debarshi29/debarshi29/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/debarshi29/debarshi29/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/debarshi29/debarshi29/output/github-snake-dark.svg" />
</picture>

> to generate the snake: copy `.github/workflows/snake.yml` into your repo, enable Actions write permissions, and run once manually.

---

<div align="center">

*building in interpretability · agents · distributed inference*<br/>
*reach out if any of that overlaps*

<br/>

[![](https://img.shields.io/badge/↗_debarshi29.github.io-0d1117?style=for-the-badge&logo=Firefox&logoColor=58a6ff)](https://debarshi29.github.io)

<img src="https://komarev.com/ghpvc/?username=debarshi29&color=58a6ff&style=flat-square&label=views" />

</div>
