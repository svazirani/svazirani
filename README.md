<h1 align="center">Soham Vazirani</h1>

<p align="center">
  <b>I use machine learning on problems that are too slow, expensive, or risky to solve head-on.</b><br/>
  Physics simulations · AI agent security · financial markets
</p>

<p align="center">
  Data Science, Economics &amp; Mathematics @ UW–Madison · graduating Dec 2027<br/>
  <a href="https://linkedin.com/in/soham-vazirani">LinkedIn</a> ·
  <a href="mailto:sohamvazirani@gmail.com">Email</a> ·
  <a href="https://pypi.org/project/tripwire-eval/">tripwire-eval on PyPI</a>
</p>

<br/>

I've been into markets since I started investing at 12. That pulled me into quantitative finance, and then into a broader habit: when a problem is too costly to solve directly, build a model that learns it and measure honestly whether it worked.

- **Researching** graph neural networks for subsurface transport with Prof. Christopher Zahasky (paper in progress)
- **Building** Tripwire, an open-source red-teaming harness for AI agents, now being written up as a paper
- **Looking for** Summer 2027 internships in quantitative research and ML/AI engineering
- **Off the keyboard:** varsity table tennis and president of UW–Madison's Table Tennis Club. Mumbai → Madison

<br/>

## Graph neural networks for subsurface physics

<sub>Research · Zahasky Lab, UW–Madison · PyTorch Geometric · code private until publication</sub>

Predicting how a contaminant spreads through underground fractures normally means running a full physics simulation for every network you want to study. I train graph neural networks that learn that transport straight from the network's structure, so hundreds of scenarios can be evaluated in the time a single simulation takes.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/gnn-dark.svg">
  <img src="assets/gnn-light.svg" alt="A fracture network drawn as a directed graph feeds a six-layer message-passing GNN, which predicts the breakthrough curve a physics simulation would produce" width="100%">
</picture>

- 6-layer directed message-passing GNN, **100–1000× faster** than the physics simulator across 80,000 realizations
- Standardized features spanning 8 orders of magnitude, reaching **~0.012 median error** with 98% of test cases under threshold
- Now building a graph variational autoencoder that compresses networks of any size into a fixed latent space

<br/>

## [Tripwire](https://github.com/Arunjay4213/Tripwire): can a prompt injection hijack your AI agent?

<sub>SAIL @ UW–Madison · team of four · Python · LangGraph · CrewAI · AgentDojo · <code>pip install tripwire-eval</code></sub>

Agents that read emails, tickets, and web pages can be steered by instructions hidden inside them. Tripwire plants a secret, attacks the agent with a suite of injections, and checks in plain Python, with no LLM judge, whether the secret reached someone it shouldn't. Then it tells you which defense fixes it.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/tripwire-dark.svg">
  <img src="assets/tripwire-light.svg" alt="Bar chart: with no defense, prompt injections leaked the secret 71% of the time; prompt hardening 18%; spotlighting 13%; guard, egress scan, allowlist and quarantined reader 0%, with task completion between 77% and 100%" width="100%">
</picture>

- I built the framework-agnostic adapter layer (LangGraph, CrewAI, tool-loop agents) and pushed the product side: bring-your-own-agent CLI, pip install, and a CI gate that fails builds when attack success crosses a threshold
- 26,880 episodes across two frontier models, plus adaptive attackers (PAIR, TAP) whose payloads were replayed on held-out seeds
- The deterministic judge agreed with blind hand labels on 30 of 30 episodes; 850+ offline tests

<br/>

## [Assay](https://github.com/svazirani/Badger-Build-Fest): when does an AI task actually need the expensive model?

<sub>🏆 1st place Databricks track, 3rd overall · Badger BuildFest 2026 · Databricks · FastAPI · Delta Lake · <a href="https://www.youtube.com/watch?v=Xhl1AXFDvE8">demo video</a> · <a href="https://devpost.com/software/undecided-dsevk2">Devpost</a></sub>

When eight LLMs said they were at least 95% sure, they were wrong 1,793 times out of 2,321. Assay grades models against what the Apache maintainers actually did, and only lets an agent act alone, or drop to a cheaper model, when the statistics back it up.

<img src="assets/assay-dashboard.png" alt="Assay dashboard: 1,362 tickets evaluated, 5,125 answers verified, 1,793 of 2,321 high-confidence answers were false positives, 35 claims decided" width="100%">

- Ingested 37,853 Jira tickets into Unity Catalog, graded 8 LLMs, and shipped the dashboard as a Databricks App
- Clopper-Pearson 95% bounds certify which patterns are safe to automate, routing work to a model **57% cheaper** with no significant precision loss

<br/>

## More

**[Crypto return forecasting](https://github.com/svazirani/Cryptocurrency-Return-Forecasting)** · <sub>STAT 453 team project · PyTorch</sub><br/>
A three-stream CNN–GRU combining price, on-chain, and sentiment data to forecast next-day Bitcoin returns. It cut MAE by 74% against a rolling ARIMA baseline and reached 56.6% directional accuracy (vs. 52.6%), a good reminder that a better forecast is not automatically a profitable strategy.

**Experience**

- Deep Learning Research Assistant · Zahasky Lab, UW–Madison · 2026–present
- Quantitative Analyst Intern · Shepherd Ventures · built Spark and Bloomberg data pipelines and a LangGraph research agent; lifted portfolio downside protection from 30% to 40%
- AI Research Intern · GrowYT · profiled generative-AI adoption across 50+ organizations
- Course Assistant, Linear Algebra (MATH 340) · office hours for 100+ students

**Toolkit**<br/>
Python · SQL · R · Java · PyTorch · PyTorch Geometric · TensorFlow · scikit-learn · LangGraph · CrewAI · Spark · Kafka · Databricks · Snowflake · MongoDB · AWS · Docker · FastAPI

<details>
<summary><b>Coursework</b></summary>
<br/>
Big Data Systems · Deep Learning · Mathematical Methods for Data Science · Artificial Intelligence · Probability · Linear Algebra · Econometrics · Money &amp; Banking
</details>

<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake-dark.svg">
    <img alt="A snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/svazirani/svazirani/output/github-snake.svg">
  </picture>
</p>
