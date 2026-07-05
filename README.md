<h1 align="center">Sreekant Baheti</h1>

<p align="center"><b>M.S. Computer Science · Los Angeles, CA</b></p>

<p align="center"><i>Building AI systems that ship: agentic LLM pipelines, healthcare ML, and the engineering rigor in between.</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/sreekantbaheti/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:sreekantbaheti13@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://www.sreekantbaheti.com/Resume.pdf">
    <img src="https://img.shields.io/badge/Resume-FF7139?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Resume"/>
  </a>
  <a href="https://github.com/Sreekant13">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a
  href="https://sreekantbaheti.com">
    <img src="https://img.shields.io/badge/Portfolio-6F42C1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
</p>

---

## About Me

I'm a recent **M.S. Computer Science graduate from USC (May 2026)** with a background in software and machine learning engineering. I've worked across banks, fintech, and AI startups, and I like problems that sit at the intersection of well-designed systems and real machine learning, where the work has to be correct, fast, and shippable.

Right now I'm focused on **agentic LLM systems, applied NLP, and ML for healthcare**. I care a lot about the production side: containerized inference, CI/CD, fine-tuning that actually moves a metric, and pipelines that don't fall over at 1,200 requests an hour.

🔭 **Currently:** contributing to open-source ML libraries and fine-tuning an open model to publish on Hugging Face Hub.

Outside of code, I think about sustainability, interdisciplinary AI, and the bigger questions about why any of this matters.

---

## Technical Skills

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Machine Learning & AI**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Unsloth](https://img.shields.io/badge/Unsloth-7B68EE?style=flat&logoColor=white)

**Data & Streaming**
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat&logo=temporal&logoColor=white)

---

## Featured Projects

### Orq: AI Incident Response Operator
A production-style incident response orchestrator built on a 10-node **Temporal DAG**, with Claude-powered root cause analysis driving the diagnostic path. Tested across 230+ synthetic incidents, with **MTTR dropping from 47 minutes to 18 minutes**.
*TypeScript · Next.js · Temporal · Claude API · Railway*

### relevant-priors-api
A FastAPI service for **radiology prior relevance prediction**, deployed on Render. TF-IDF with n-gram features feeding a scikit-learn classifier, hitting **98.27% accuracy on the public smoke-test set**. Designed to slot into a healthcare ML workflow as a low-latency relevance scorer.
*Python · FastAPI · scikit-learn · Render*

### LLaMA 3.2 Vision LoRA Fine-Tuning
Fine-tuned a 4-bit quantized LLaMA 3.2 Vision model on the **MultiUI/GUI dataset** using Unsloth, exploring efficient multimodal adaptation under tight memory budgets.
*PyTorch · Unsloth · LoRA · LLaMA 3.2*

### [EcoMate-AI](https://github.com/Sreekant13/EcoMate-AI) &nbsp;·&nbsp; [Live Demo](https://ecomateai.streamlit.app/)
🥇 **1st Place — EcoMate AI Hackathon** (Sustainable Infrastructure category)
A Streamlit app that estimates personal carbon footprints by extracting activity data from natural-language text and images using a multimodal GenAI pipeline.
*Python · Streamlit · GenAI · Multimodal*

### JanusGraph YCSB Benchmarking
A custom **YCSB Java binding for JanusGraph**, with schema and CRUD driven through remote Gremlin traversal. Used to analyze single-node vs. multi-node performance characteristics under standard workload mixes.
*Java · JanusGraph · Gremlin · YCSB*

---

## 🔀 Open Source Contributions

Merged PRs in widely used Python & ML libraries:

- **[huggingface_hub](https://github.com/huggingface/huggingface_hub)** — 4 merged PRs: made `filter_repo_objects` pattern matching case-sensitive across platforms ([#4435](https://github.com/huggingface/huggingface_hub/pull/4435)), added two-letter byte units (KB/MB/GB/TB) to `parse_size` ([#4468](https://github.com/huggingface/huggingface_hub/pull/4468)), plus CLI help & docstring fixes ([#4477](https://github.com/huggingface/huggingface_hub/pull/4477), [#4436](https://github.com/huggingface/huggingface_hub/pull/4436))
- **[networkx](https://github.com/networkx/networkx)** — aligned `boruvka_mst_edges` defaults with Kruskal/Prim ([#8728](https://github.com/networkx/networkx/pull/8728))
- **[dpgen](https://github.com/deepmodeling/dpgen)** — fixed an `AttributeError` in ABACUS Gamma post-processing ([#1920](https://github.com/deepmodeling/dpgen/pull/1920))
- **[xarray](https://github.com/pydata/xarray)** — docstring fix in `cumulative()` ([#11425](https://github.com/pydata/xarray/pull/11425))
- **[statsmodels](https://github.com/statsmodels/statsmodels)** — docstring fixes ([#9873](https://github.com/statsmodels/statsmodels/pull/9873))

[**All merged PRs →**](https://github.com/search?q=author%3ASreekant13+is%3Apr+is%3Amerged&type=pullrequests)

---

## Experience Highlights

- **Software Engineer Intern** at **The Verse** (May - Aug 2025): Agentic LLM pipelines across 47 daily workflows, BART entity extractor fine-tuned from **0.74 to 0.91 F1**, containerized inference handling 1,247 req/hr at peak.
- **Software Engineer** at **Bank of America**: Production backend systems and data workflows; automated **Kafka topic & role provisioning** (Enterprise-Level Silver Award).
- **Software Engineering Intern** at **HighRadius**: AI-Enabled FinTech B2B invoice management using XGBoost.

---

## 🏆 Achievements

- 🥈 **Enterprise-Level Silver Award, Bank of America** — for automating Kafka topic & role provisioning, replacing a manual multi-team workflow.
- 🥇 **1st Place, EcoMate AI Hackathon** — Sustainable Infrastructure category, for [EcoMate-AI](https://github.com/Sreekant13/EcoMate-AI) ([live demo](https://ecomateai.streamlit.app/)), a multimodal GenAI carbon-footprint estimator.
- 🔀 **Open-source contributor** — merged PRs in Hugging Face Hub, NetworkX, xarray, statsmodels, and dpgen ([details above](#-open-source-contributions)).

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sreekant13&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sreekant13&layout=compact&theme=tokyonight&hide_border=true&hide=jupyter%20notebook,html,css&langs_count=8" alt="Top Languages" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Sreekant13&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

## Beyond Code

- Long-standing interest in **reinforcement learning, evolutionary optimization, and applied LLM research**.
- Thinking a lot about **AI for healthcare and education**, plus **sustainability** as a design constraint, not an afterthought.
- Curious about the deeper why behind the work: spirituality, meaning, and what good engineering owes the people it touches.

---

<p align="center"><i>Open to opportunities in ML engineering, software engineering, NLP, and healthcare AI.</i></p>
