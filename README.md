<h1 align="center">Data & AI Engineering</h1>
<h3 align="center">Building resilient data, ML and agentic pipelines</h3>

<p align="center">
  <a href="https://annafp.online">
    <img src="https://img.shields.io/badge/🌐_portfolio-annafp.online-1f6feb?style=for-the-badge" alt="portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/anna-falceto-pinyol/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/based%20in-Heidelberg%20🇩🇪-informational?style=flat-square" alt="location" />
</p>

---

I'm Anna and I work across **data platforms, ML systems and agentic pipelines**.
I build ingestion and RAG pipelines that stay consistent under real traffic; ML services shielded by schema contracts, circuit breakers and drift kill-switches; and **LangGraph agents** with dynamic routing, tool orchestration, evaluator-optimizer loops and human-in-the-loop gates, grounded in structured LLM evaluation (LangSmith, RAGAS, LLM-as-judge) so the behaviour is measurable, not vibes.

I care about **resilience over cleverness**, **observability over demos**, and earning complexity before adding it; especially in agents, where the wrong abstraction is expensive.

---

### 🛠 Stack

**Agents & LLMs**
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square)
![LangChain](https://img.shields.io/badge/-LangChain-121212?style=flat-square)
![LangSmith](https://img.shields.io/badge/-LangSmith-3ECF8E?style=flat-square)
![RAGAS](https://img.shields.io/badge/-RAGAS-6E44FF?style=flat-square)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**ML & MLOps**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-006ACC?style=flat-square)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Data & Storage**
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Qdrant](https://img.shields.io/badge/-Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-FF6B35?style=flat-square)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square)

**Backend & Infra**
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 🚀 Featured projects

#### 🔍 [LLM Lens](https://github.com/thebluetonguegiraffe/llm_lens)
Agentic website auditor that inspects how a site is perceived, indexed and represented by LLMs. A **multi-node LangGraph agent** with dynamic routing, tool orchestration and human-in-the-loop gates crawls, evaluates and reports on visibility, structure and semantic clarity from a model's point of view. Built as a study in agentic architecture done deliberately; every added node earns its place against a simpler alternative.
`LangGraph · LangSmith · FastAPI · Python`

#### 🔬 [ML Resilience Lab](https://github.com/thebluetonguegiraffe/ml_resiliance_lab)
Real-time credit card fraud detection on a **5-layer Medallion streaming architecture**, shielded by a multi-layer defense system: Pydantic schema contracts at ingestion, a **state-driven Circuit Breaker** with instant fallback on enrichment API outages, and a **data drift Kill Switch** that halts the pipeline when live distributions deviate beyond 80%. Random Forest model registered via MLflow; AUPRC 0.931, 5 false negatives on 284K records. Interactive chaos engineering panel to inject faults and audit resilience patterns live.
`Python · Pydantic · MLflow · MongoDB · Next.js · Docker`

#### 🎨 [ArtGuide](https://github.com/thebluetonguegiraffe/artguide)
Multimodal AI museum guide: point a camera at a painting and get spoken narration in real time. A **LangGraph agent** orchestrates a **cost-optimised hybrid RAG**: self-hosted CLIP embeddings and Qdrant vector search as the primary path, GPT-4o deep search reserved for low-confidence edge cases. Neural TTS synthesis via self-hosted Piper (ONNX, CPU inference) across three languages. Full control over the serving layer, no third-party inference dependencies.
`LangGraph · CLIP · Qdrant · GPT-4o · Piper TTS · FastAPI`

#### 📰 [The News Hub](https://github.com/thebluetonguegiraffe/the_news_hub)
Automated news aggregation and analysis platform. **Dual-source Airflow pipeline** (Crawl4AI + Finlight API) ingesting 3,000+ articles/month with hot-swappable DAGs for zero-downtime updates. Unsupervised topic clustering (PCA + K-Means + GPT-4o labelling) auto-segments the stream into trending themes with no manual annotation. Hybrid storage (ChromaDB + MongoDB) exposed via FastAPI with a RAG endpoint for natural-language querying over the live corpus.
`Airflow · LangGraph · ChromaDB · MongoDB · FastAPI · Docker`

---

<p align="center">
  <b>Full case studies, write-ups and live demos on my portfolio</b>
  <br><br>
  <a href="https://annafp.online">
    <img src="https://img.shields.io/badge/→_visit_annafp.online-1f6feb?style=for-the-badge" alt="portfolio" />
  </a>
</p>

---

### 📊 Stats

<p align="center">
  <img height="165" src="https://github-readme-stats-one-pi-27.vercel.app/api?username=thebluetonguegiraffe&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats-one-pi-27.vercel.app/api/top-langs/?username=thebluetonguegiraffe&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=thebluetonguegiraffe&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center"> <img src="https://nomlings.cc/badge/thebluetonguegiraffe?pet=byteling&color=%23FFD700&scale=5" alt="my byteling eats my commits" /> </p>
