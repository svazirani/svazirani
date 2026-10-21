<h1 align="center">Soham Vazirani</h1>

<p align="center">
  <b>I use machine learning on problems that are too slow, expensive, or risky to solve head-on.</b><br/>
  Data Science · Economics · Mathematics @ UW–Madison · graduating Dec 2027
</p>

<p align="center">
  <a href="https://linkedin.com/in/soham-vazirani"><img src="https://img.shields.io/badge/LinkedIn-1f2328?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sohamvazirani@gmail.com"><img src="https://img.shields.io/badge/Email-1f2328?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://pypi.org/project/tripwire-eval/"><img src="https://img.shields.io/pypi/v/tripwire-eval?style=flat-square&label=tripwire-eval&color=1f2328" alt="tripwire-eval on PyPI"/></a>
</p>

## About me

I'm a Data Science, Economics, and Mathematics student at UW–Madison interested in using technology and analytical thinking to solve interesting problems. I enjoy exploring new ideas, building things from scratch, and learning how complex systems work, whether that's through machine learning research, AI projects, or quantitative finance. I'm always looking for opportunities to challenge myself, work with people who think differently, and turn ideas into something meaningful.

- 🔬 **Researching** graph neural networks for subsurface physics with Prof. Christopher Zahasky
- 🛡️ **Building** Tripwire, an open-source red-teaming harness for AI agents
- 💼 **Looking for** Summer 2027 internships in quant research and ML/AI engineering
- 🏓 **Off the keyboard:** varsity table tennis and Treasurer of UW–Madison's Table Tennis Club

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### Fracture-Flow GNN Surrogate
**Current research** · Subsurface Hydrophysics Lab, UW–Madison

Graph neural networks that learn how contaminants move through underground fracture networks, standing in for expensive physics simulations.

- **100–1000× faster** than simulation across 80,000 realizations
- **~0.012 median error**, with 98% of test cases under threshold
- Next: a graph VAE for networks of any size, paper in progress

`PyTorch Geometric` `GNNs` `Scientific ML`

</td>
<td width="50%" valign="top">

### [Tripwire](https://github.com/Arunjay4213/Tripwire)
**Published on PyPI** · SAIL @ UW–Madison

A red-teaming harness that measures how easily tool-using AI agents get hijacked by prompt injection, scored by a deterministic check instead of an LLM judge.

- Undefended agents leaked the secret in **71%** of attacks; a recipient allowlist cut that to **0%**
- 26,880 test runs on two frontier models and 850+ offline tests
- I built the cross-framework adapter layer (LangGraph, CrewAI, tool loops)

`pip install tripwire-eval` `LangGraph` `CrewAI` `AgentDojo`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Assay](https://github.com/svazirani/Badger-Build-Fest)
**🏆 1st Databricks track, 3rd overall**

Built at Badger BuildFest: an AI agent manager that uses statistical evidence to decide which LLM to use and when an agent may act on its own.

- When 8 LLMs claimed 95%+ confidence, they were wrong **1,793 of 2,321** times
- Routed work to a model **57% cheaper** with no significant precision loss
- 37,853 Jira tickets in Unity Catalog · [demo video](https://www.youtube.com/watch?v=Xhl1AXFDvE8)

`Databricks` `FastAPI` `Delta Lake`

</td>
<td width="50%" valign="top">

### [Crypto Return Forecasting](https://github.com/svazirani/Cryptocurrency-Return-Forecasting)
**Working paper** · STAT 453 team project

A three-stream CNN–GRU that fuses price, on-chain, and sentiment data to forecast next-day Bitcoin returns.

- **74% lower MAE** than a rolling ARIMA baseline
- **56.6%** directional accuracy vs. 52.6% for the baseline
- A reminder that a better forecast isn't automatically a profitable strategy

`PyTorch` `pandas` `SQL`

</td>
</tr>
</table>

## Experience

| Role | Where | When |
|:--|:--|:--|
| Deep Learning Research Assistant | Subsurface Hydrophysics Lab, UW–Madison | May 2026 – now |
| Quantitative Analyst Intern | Shepherd Ventures | Oct 2025 – May 2026 |
| Course Assistant, Linear Algebra | UW–Madison Math Learning Center | Aug 2025 – May 2026 |
| AI Research Intern | GrowYT | Feb 2025 – May 2025 |

## Toolkit

<table>
<tr><td><b>Languages</b></td><td><img src="https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/SQL-1f2328?style=flat-square&logo=databricks&logoColor=white" alt="SQL"/> <img src="https://img.shields.io/badge/R-1f2328?style=flat-square&logo=r&logoColor=white" alt="R"/> <img src="https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/></td></tr>
<tr><td><b>ML &amp; AI</b></td><td><img src="https://img.shields.io/badge/PyTorch-1f2328?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/PyTorch_Geometric-1f2328?style=flat-square&logo=pyg&logoColor=white" alt="PyG"/> <img src="https://img.shields.io/badge/TensorFlow-1f2328?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/> <img src="https://img.shields.io/badge/scikit--learn-1f2328?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/> <img src="https://img.shields.io/badge/LangGraph-1f2328?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/> <img src="https://img.shields.io/badge/CrewAI-1f2328?style=flat-square&logoColor=white" alt="CrewAI"/></td></tr>
<tr><td><b>Data &amp; Infra</b></td><td><img src="https://img.shields.io/badge/Spark-1f2328?style=flat-square&logo=apachespark&logoColor=white" alt="Spark"/> <img src="https://img.shields.io/badge/Kafka-1f2328?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka"/> <img src="https://img.shields.io/badge/Databricks-1f2328?style=flat-square&logo=databricks&logoColor=white" alt="Databricks"/> <img src="https://img.shields.io/badge/Snowflake-1f2328?style=flat-square&logo=snowflake&logoColor=white" alt="Snowflake"/> <img src="https://img.shields.io/badge/MongoDB-1f2328?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"/> <img src="https://img.shields.io/badge/AWS-1f2328?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/> <img src="https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/></td></tr>
</table>


**Coursework:** Big Data Systems · Deep Learning · Mathematical Methods for Data Science · Artificial Intelligence · Probability · Linear Algebra · Econometrics · Money & Banking

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake.svg" />
  </picture>
</p>
