# Hi there!

<img src="https://media.tenor.com/mvz4g0C0SQYAAAAM/garfield.gif" alt="Greeting gif" width="250"/>

---

## About Me

* Data Scientist / ML Infrastructure Engineer with an engineering background
* Platform & ML infrastructure engineer for a large AI research division: self-hosted services, observability, LLM gateways, AI-agent tooling
* Data annotation manager (team of 8–14 people)
* Experience in R\&D projects involving LLMs, CV, and time series
* Production experience with LLM infrastructure, RAG systems, and large-scale inference
* Hands-on experience serving DeepSeek, GLM, and Qwen model families on multi-node GPU clusters
* Teaching experience: courses on ML, CV, and Time Series

---

## Experience Highlights

* **Sberbank — Lead Infrastructure Engineer** *(Sep 2025 — Present)*
  * Deployed and maintained multi-node inference infrastructure for large LLMs: DeepSeek v4, GLM 5.1, GLM 5.3 Flash, Qwen 2.5, Qwen 3, Qwen 3.5, including dense and MoE models from 4B to 400B parameters.
  * Worked with SLURM job orchestration and GPU cluster operations across up to 16 H100 nodes and 8 A100 nodes.
  * Built Docker images, configured recent vLLM versions, tuned model serving parameters, and improved model throughput.
  * Deployed and operated internal platform services for 50–60 researchers: GitLab (CE→EE migration, Pages, runners), self-hosted Overleaf (OIDC SSO, automated backups), CryptPad, mail service, ClearML, and CI/CD templates for multi-contour deployment.
  * Built an observability stack: Grafana + Prometheus monitoring for GPU clusters, NFS/tenant metrics, and log aggregation across the VPS fleet.
  * Built an internal OpenAI-compatible inference gateway with API-key management, per-user token usage analytics, GitLab group-based access control, and vLLM benchmarking.
  * Developed a Telegram-facing AI-agent platform (Hermes-based): user profile separation, incident reporting, MCP tooling, and GPU resource management via Cloud.ru API.
  * Ran the edge layer: Traefik/Nginx with automatic TLS, FRP tunneling for demo services, and a reusable OAuth2 SSO gate across internal domains.
  * Managed infrastructure capacity and GPU resource allocation between research teams; handled S3/OBS bucket lifecycle, incident response, and data transfers between compute contours.
  * Built research and demo tooling: multimodal search demo (Qdrant/Postgres ingestion pipeline over 40+ auction sources), inference monitoring portal, demo-analytics service, conference digest bot, LaTeX build service, and MR-review agent.

---

## Education

* Specialist degree, Saratov State University (2025, with honors)
* Field of study: *Mathematical Methods of Information Security*

---


## Tech Stack

### Programming Languages
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
</p>

### ML / DL / NLP / CV
<p>
  <img src="https://img.shields.io/badge/Torch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Transformers-F8BF3C?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/LLM-4B0082?style=for-the-badge" alt="LLM"/>
  <img src="https://img.shields.io/badge/vLLM-111827?style=for-the-badge" alt="vLLM"/>
  <img src="https://img.shields.io/badge/RAG-006400?style=for-the-badge" alt="RAG"/>
  <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-2E8B57?style=for-the-badge" alt="Seaborn"/>

</p>

### Backend / DevOps
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/SLURM-2E8B57?style=for-the-badge" alt="SLURM"/>
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"/>
  <img src="https://img.shields.io/badge/ClearML-5A4FCF?style=for-the-badge" alt="ClearML"/>
</p>

### Databases & Orchestration
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/ClickHouse-FFCC00?style=for-the-badge&logo=clickhouse&logoColor=black"/>
  <img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dagster-8E24AA?style=for-the-badge"/>
</p>

---

## 📄 Most cited papers

1. **Deep learning approaches to automatic chronic venous disease classification (35 citations)**  
   *Barulina, M.; Sanbaev, A.; Okunkov, S.; Ulitin, I.; Okoneshnikov, I.*  
   *Mathematics*, **10**(19), 3571, 2022 — MDPI  
   🔗 [DOI:10.3390/math10193571](https://doi.org/10.3390/math10193571)

2. **Sensitivity of modern deep learning neural networks to unbalanced datasets in multiclass classification problems (18 citations)**  
   *Barulina, M.; Okunkov, S.; Ulitin, I.; Sanbaev, A.*  
   *Applied Sciences*, **13**(15), 8614, 2023 — MDPI  
   🔗 [DOI:10.3390/app13158614](https://doi.org/10.3390/app13158614)

3. **An Overview of Using Deep Learning Algorithms for Anemia Detection (5 citations)**  
   *Barulina, M.; Ulitin, I.; Kaluta, T.; Fedonnikov, A.*  
   *Artificial Intelligence in Engineering and Science (AI2ES 2022)*, Springer, pp. 605–615  
   🔗 [Springer Link](https://link.springer.com/chapter/10.1007/978-3-031-22938-1_41)


---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=QQQiwi&show_icons=true&theme=radical&count_private=true&include_all_commits=true" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=QQQiwi&layout=compact&theme=radical&langs_count=10" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=QQQiwi&theme=radical&hide_border=false" />
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=QQQiwi&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views" />
</p>

---

## Contacts

<p align="center">
  <a href="https://t.me/qqq_iwi" target="_blank"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
  <a href="mailto:qqqiwi.prog@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>
