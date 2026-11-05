### Hey there, I'm Mounika 👋

I'm a machine learning engineer who likes taking models out of notebooks and into real systems. I build MLOps pipelines, RAG agents, and LLM tools, and I measure every change before I trust it.

<p>
<a href="https://www.linkedin.com/in/mounikagajja/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://YOUR-PORTFOLIO.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="mailto:mounikagajja@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### 🔭 Right now

- Looking for **Machine Learning Engineer** and **AI Engineer** roles
- Exploring **MCP** and agent tooling

---

### 🛠️ Things I've built

**🚕 NYC Taxi MLOps Pipeline** · [repo](https://github.com/mounikagajja/nyc-taxi-mlops)  
Raw data to a monitored, containerized model.
- Ingested ~2.86M taxi records into Delta Lake with PySpark on Databricks
- LightGBM trip duration model tracked in MLflow, RMSE ~5 min on ~549K holdout rows
- Served with FastAPI and Docker, tested in GitHub Actions CI
- KS-test drift check flagged drift in all 8 features between January and February

**🧠 LangGraph-Brain** · [repo](https://github.com/mounikagajja/langgraph-brain)  
A RAG agent that answers questions about LangGraph from its issues, PRs, and docs.
- Qdrant vector search over a 17K-chunk knowledge base, exposed through FastMCP
- Cross-encoder reranking raised context relevance 32% (0.39 to 0.52) across a 4-version ablation on a 50-question test set
- Self-critique retry loop reached a 92% citation rate and cut manual review escalation to 56%

**🏦 SentinelBank** · [repo](https://github.com/mounikagajja/sentinelbank)  
Full-stack banking app with real-time fraud detection and an AI banking assistant, built entirely on free tiers.
- Engineered behavioral fraud features on 32K+ transactions, raising XGBoost PR-AUC from 0.77 to 0.83 (ROC-AUC 0.99), tracked in MLflow
- Real-time scoring on Redpanda with idempotent writes, so replayed events never create duplicate fraud flags
- Batch-vs-online parity test guards against training-serving skew, backed by 57 automated tests
- FastAPI service with JWT role-based access and a LangGraph banking assistant, all on free tiers

---

### 🧰 Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)

---

### 📜 Certifications

LLM Engineering with RAG (Coursera) · Fundamentals of MCP (Hugging Face) · Google Cloud ML Engineer path badge · IBM Python for Data Science, AI and Development · IBM Introduction to Data Engineering
