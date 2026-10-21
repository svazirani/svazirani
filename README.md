<h1 align="center">Soham Vazirani</h1>

<p align="center">
  Data Science · Economics · Mathematics @ UW–Madison<br/>
  I build ML systems: graph neural nets for science, evaluation tooling for AI agents, and models for markets.
</p>

<p align="center">
  <a href="https://linkedin.com/in/soham-vazirani"><img src="https://img.shields.io/badge/LinkedIn-1f2328?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sohamvazirani@gmail.com"><img src="https://img.shields.io/badge/Email-1f2328?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://pypi.org/project/tripwire-eval/"><img src="https://img.shields.io/pypi/v/tripwire-eval?style=flat-square&label=tripwire-eval&color=1f2328" alt="tripwire-eval on PyPI"/></a>
</p>

---

### About

- **Now:** Deep learning research in the Dept. of Geoscience with Prof. Christopher Zahasky, building GNN surrogates for fracture-network flow
- **Before:** Quant Analyst Intern @ Shepherd Ventures · AI Research Intern @ GrowYT · Course Assistant for MATH 340
- **Into:** quantitative finance, ML systems, and startups. I like hackathons more than I probably should
- **Off the keyboard:** varsity table tennis at UW–Madison and club president. Mumbai → Madison
- **Open to:** Summer 2027 internships in quant research, ML, and AI engineering

### Featured Work

<table>
<tr>
<td width="50%" valign="top">

<b><a href="https://github.com/Arunjay4213/Tripwire">Tripwire</a></b> · <code>pip install tripwire-eval</code><br/>
<sub>SAIL @ UW–Madison · Python · LangGraph · CrewAI · AgentDojo</sub>
<p>Red-teaming harness that measures how easily tool-using AI agents get hijacked by indirect prompt injection, scored by a deterministic canary check with no LLM judge.</p>
<ul>
<li>Built the framework-agnostic adapter layer (LangGraph, CrewAI, tool-loop agents)</li>
<li>CI gate fails builds when attack-success rate crosses a threshold; 351 offline tests</li>
</ul>

</td>
<td width="50%" valign="top">

<b><a href="https://github.com/svazirani/Badger-Build-Fest">Assay</a></b> · 1st Databricks Track, 3rd Overall<br/>
<sub>Badger BuildFest · Databricks · FastAPI · Delta Lake</sub>
<p>AI agent governance platform that uses statistical evidence to decide which LLM to use and when an agent is allowed to act on its own.</p>
<ul>
<li>Ingested 37,853 Jira tickets into Unity Catalog and graded 8 LLMs</li>
<li>Clopper-Pearson 95% bounds routed work to a model 57% cheaper with no significant precision loss</li>
</ul>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<b>Fracture-Flow GNN Surrogate</b> · current research<br/>
<sub>Subsurface Hydrophysics Lab · PyTorch Geometric · code private</sub>
<p>A 6-layer directed message-passing GNN that stands in for physics simulations of solute transport through fracture networks.</p>
<ul>
<li>100–1000× faster than simulation across 80,000 realizations, ~0.012 median error</li>
<li>Next: a graph VAE compressing variable-size networks into a fixed latent space (paper in progress)</li>
</ul>

</td>
<td width="50%" valign="top">

<b><a href="https://github.com/svazirani/Cryptocurrency-Return-Forecasting">Crypto Return Forecasting</a></b> · working paper<br/>
<sub>PyTorch · pandas · SQL</sub>
<p>Three-stream CNN–RNN model (price, on-chain, sentiment) forecasting next-day Bitcoin log-returns.</p>
<ul>
<li>74% lower MAE than a rolling ARIMA(5,1,0) baseline</li>
<li>56.6% directional accuracy vs. 52.6% for the baseline</li>
</ul>

</td>
</tr>
</table>

### Toolkit

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-1f2328?style=flat-square&logo=databricks&logoColor=white) ![R](https://img.shields.io/badge/R-1f2328?style=flat-square&logo=r&logoColor=white) ![Java](https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white) |
| **ML & AI** | ![PyTorch](https://img.shields.io/badge/PyTorch-1f2328?style=flat-square&logo=pytorch&logoColor=white) ![PyG](https://img.shields.io/badge/PyTorch_Geometric-1f2328?style=flat-square&logo=pyg&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-1f2328?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1f2328?style=flat-square&logo=scikitlearn&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1f2328?style=flat-square&logo=langchain&logoColor=white) ![CrewAI](https://img.shields.io/badge/CrewAI-1f2328?style=flat-square&logoColor=white) |
| **Data & Infra** | ![Spark](https://img.shields.io/badge/Spark-1f2328?style=flat-square&logo=apachespark&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-1f2328?style=flat-square&logo=apachekafka&logoColor=white) ![Databricks](https://img.shields.io/badge/Databricks-1f2328?style=flat-square&logo=databricks&logoColor=white) ![Snowflake](https://img.shields.io/badge/Snowflake-1f2328?style=flat-square&logo=snowflake&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-1f2328?style=flat-square&logo=mongodb&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-1f2328?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=white) |

### Coursework

Big Data Systems · Deep Learning · Mathematical Methods for Data Science · Artificial Intelligence · Probability · Linear Algebra · Econometrics · Money & Banking

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake.svg" />
  </picture>
</p>
