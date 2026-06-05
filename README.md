<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&multiline=false&width=700&height=60&lines=debarshi+chakraborty;multi-agent+systems;mechanistic+interpretability;distributed+systems)](https://debarshi29.github.io)

<br/>

[![Portfolio](https://img.shields.io/badge/↗_portfolio-0d1117?style=for-the-badge&logo=githubpages&logoColor=58a6ff)](https://debarshi29.github.io)
[![LinkedIn](https://img.shields.io/badge/linkedin-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff)](https://linkedin.com/in/debarshi29)
[![IEEE](https://img.shields.io/badge/IEEE_published-0d1117?style=for-the-badge&logo=ieee&logoColor=58a6ff)](https://doi.org/10.1109/WCONF64849.2025.11233239)
[![Email](https://img.shields.io/badge/email-0d1117?style=for-the-badge&logo=gmail&logoColor=58a6ff)](mailto:debarshi2933@gmail.com)

</div>

<br/>

---

<img align="right" width="360" src="https://github-readme-stats.vercel.app/api/top-langs/?username=debarshi29&layout=donut&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=8" />

### `> whoami`

```python
debarshi = {
  "degree"  : "M.Sc. Big Data Analytics · RKMVERI",
  "domains" : [
      "multi-agent systems",
      "mechanistic interpretability",
      "distributed systems",
  ],
  "question": "what neural networks do — and *why*",
  "signal"  : "0% or 100%",
}
```

<br clear="right"/>

---

### `> ls -la projects/`

<br/>

<details open>
<summary><b>🧠 THGNN-MaGNet</b> &nbsp;·&nbsp; hypergraph GNN + 6-agent LangGraph · NIFTY 500</summary>
<br/>

```
┌─────────────────────────────────────────────────────────────┐
│  rank-IC   0.0398   (+95% baseline)                         │
│  ICIR      0.420                                            │
│  Sharpe    3.71     (annualised, 583-day holdout)           │
│  latency   ~47s     end-to-end inference                    │
└─────────────────────────────────────────────────────────────┘
```

**Architecture:** BiGRU MAGE encoder → Sparse MoE routing → TCH + GPH dual hypergraph → differentiable Spearman IC loss  
**Pipeline:** `GNN` → `FinBERT sentiment` → `portfolio fusion (α-weighted)` → `risk profiler` → `macro regime` → `Gemma-4-31b report`

![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=58a6ff)
![LangGraph](https://img.shields.io/badge/LangGraph-0d1117?style=flat-square&logo=langchain&logoColor=58a6ff)
![FinBERT](https://img.shields.io/badge/FinBERT-0d1117?style=flat-square&logo=huggingface&logoColor=58a6ff)
![Streamlit](https://img.shields.io/badge/Streamlit-0d1117?style=flat-square&logo=streamlit&logoColor=58a6ff)

</details>

<br/>

<details open>
<summary><b>⛓️ T+0 Trade Settlement</b> &nbsp;·&nbsp; blockchain-native · <a href="https://doi.org/10.1109/WCONF64849.2025.11233239">IEEE WCONF 2025</a></summary>
<br/>

```
┌─────────────────────────────────────────────────────────────┐
│  finality          < 2s    (IBFT-2 BFT consensus)           │
│  risk reduction    91.7%   (vs baseline settlement)         │
│  network           4-node Hyperledger Besu                  │
│  compliance        LangGraph state machines · Llama 3.2     │
└─────────────────────────────────────────────────────────────┘
```

**Fraud:** XGBoost scores every trade off-chain before it touches the ledger → SHAP + LIME surface the why

![Hyperledger](https://img.shields.io/badge/Hyperledger_Besu-0d1117?style=flat-square&logo=hyperledger&logoColor=58a6ff)
![LangGraph](https://img.shields.io/badge/LangGraph-0d1117?style=flat-square&logo=langchain&logoColor=58a6ff)
![XGBoost](https://img.shields.io/badge/XGBoost-0d1117?style=flat-square&logo=xgboost&logoColor=58a6ff)
![SHAP](https://img.shields.io/badge/SHAP+LIME-0d1117?style=flat-square&logo=python&logoColor=58a6ff)

</details>

<br/>

<details open>
<summary><b>⚡ Distributed LLM Inference</b> &nbsp;·&nbsp; DeepSeek R1 + Llama 3.2B</summary>
<br/>

```
┌─────────────────────────────────────────────────────────────┐
│  throughput   2–4×    over single-GPU baseline              │
│  strategy     tensor parallelism + pipeline parallelism     │
│  kernels      CUDA — comms overlapped with compute          │
│  interface    Python bindings                               │
└─────────────────────────────────────────────────────────────┘
```

![Rust](https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=58a6ff)
![CUDA](https://img.shields.io/badge/CUDA-0d1117?style=flat-square&logo=nvidia&logoColor=58a6ff)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=58a6ff)

</details>

<br/>

<details open>
<summary><b>🤖 NET-LINK</b> &nbsp;·&nbsp; self-healing drone swarms · MARL</summary>
<br/>

```
┌─────────────────────────────────────────────────────────────┐
│  agents       5     (shared critic, decentralized exec)     │
│  emergence    ~1200 episodes to relay-passing coordination  │
│  rules        0     no handoff logic was programmed         │
└─────────────────────────────────────────────────────────────┘
```

![MAPPO](https://img.shields.io/badge/MAPPO-0d1117?style=flat-square&logo=pytorch&logoColor=58a6ff)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0d1117?style=flat-square&logo=openaigym&logoColor=58a6ff)
![PyTorch](https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=58a6ff)

</details>

---

### `> cat stack.conf`

<div align="center">

```
languages   python · java · rust · sql
────────────────────────────────────────────────────────────
genai       pytorch · langgraph · langchain · semantic kernel
            mlflow · langfuse · pgvector · qdrant
────────────────────────────────────────────────────────────
cloud       azure · databricks · docker · kubernetes · redis
────────────────────────────────────────────────────────────
data        pyspark · pandas · polars · dbt · delta lake
────────────────────────────────────────────────────────────
research    transformerlens · huggingface · gymnasium · shap
```

</div>

---

### `> git log --stat`

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=debarshi29&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&area_color=1f6feb)](https://github.com/debarshi29)

<br/>

<table>
<tr>
<td>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=debarshi29&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=8b949e&include_all_commits=true&count_private=true)

</td>
<td>

[![GitHub Streak](https://streak-stats.demolab.com?user=debarshi29&theme=dark&hide_border=true&background=0d1117&stroke=1f6feb&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e)](https://git.io/streak-stats)

</td>
</tr>
</table>

[![trophy](https://github-profile-trophy.vercel.app/?username=debarshi29&theme=darkhub&no-frame=true&no-bg=true&margin-w=4&column=7)](https://github.com/debarshi29)

![](https://komarev.com/ghpvc/?username=debarshi29&color=1f6feb&style=flat-square&label=profile+views)

</div>

---

<div align="center">

```
// working on interpretability · multi-agent systems · distributed inference
// find me if any of that overlaps with what you're building
```

[![↗ debarshi29.github.io](https://img.shields.io/badge/↗_debarshi29.github.io-0d1117?style=for-the-badge&logo=githubpages&logoColor=58a6ff)](https://debarshi29.github.io)

</div>
