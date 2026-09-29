# Hi, I'm Omar 👋

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&pause=1000&center=true&vCenter=true&width=720&lines=Data+Engineer+%C2%B7+3+Co-ops+at+Delta+Air+Lines;Spark+%C2%B7+Databricks+%C2%B7+Delta+Lake+%C2%B7+AWS+%C2%B7+MLflow;Batch+%26+real-time+pipelines+that+people+actually+use" alt="Data Engineer · 3 Co-ops at Delta Air Lines" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/omar-elkady-847b051ba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:omitelkady1@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Atlanta,_GA-2E3440?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Atlanta, GA" />
</p>

I'm a data engineer finishing a **B.S. in Data Science at Georgia State University** (Honors College, 3.98 GPA, graduating Dec 2026). Over three co-ops at **Delta Air Lines** I've built the pipelines behind pilot training, compliance, and leadership reporting. Outside work I build end-to-end lakehouse and MLOps projects.

- ⚡ Cut a **63M-record Teradata** full refresh from **12.5 hours to under 1 hour** with incremental loads and parallel, async extracts
- ✈️ Built a daily pipeline that assigns training for **17,000+ pilots**, taking assignment latency from **15 days to same-day**
- ☁️ Set up the team's **Kubernetes DevSpaces on AWS** (IAM, Lambda triggers) by myself and onboarded 10+ engineers
- 📊 Merged Oracle, Teradata, SharePoint, and REST sources into one reporting pipeline, so a full day of manual work now takes **under 2 minutes**

---

## 🚀 Featured Projects

### ✈️ [Flight Delay Prediction Platform](https://github.com/OmaryElkady/Data-Science-Capstone)
`Databricks` `Spark ML` `Delta Lake` `Unity Catalog` `MLflow` `Asset Bundles`

Bronze → Silver → Gold Delta pipeline over **3M BTS flight records** that feeds a 2.46M-row feature store. Swapping four per-row Python UDFs for a broadcast join made it **27x faster**. Two Spark ML models are registered in Unity Catalog and scored against live flights. A one-feature baseline showed the 819-feature model added no lift, so I shifted the work to the harder pre-departure problem. **185 tests**, 4-job CI, and dev/prod Asset Bundle targets.

### 📰 [Misinformation Detection Lakehouse](https://github.com/OmaryElkady/misinformation-lakehouse)
`PySpark` `Delta Lake` `AWS S3` `RoBERTa` `MLflow` `Prefect` `FastAPI`

End-to-end MLOps platform: 36K records flow through a medallion lakehouse on S3 into a fine-tuned **RoBERTa** model (weighted F1 0.774). An MLflow promotion gate (F1 ≥ 0.80) kept the model in Staging instead of promoting it automatically. It's served through FastAPI with LLM explanations and orchestrated daily by Prefect. **116 tests at 92% coverage** and a 5-stage CI pipeline.

### ⚽ [Scout WC26: AI Scouting Agent](https://github.com/OmaryElkady/scout-wc26)
`GCP` `BigQuery` `Fivetran Connector SDK` `Gemini` `Google ADK` `Cloud Run`

Built for the Google Cloud Rapid Agent Hackathon (Fivetran track). A custom Fivetran connector lands live football data from 10 leagues in a Bronze/Silver/Gold **BigQuery** warehouse. A **Gemini 2.5 Flash** agent with 9 tools queries the Gold layer to answer scouting questions, write SQL-backed charts, and generate PDF reports. Served through FastAPI on Cloud Run, with **244 unit tests** in CI.

---

## 🛠️ Tech Stack

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Data Engineering:**
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=flat&logo=delta&logoColor=white)
![Prefect](https://img.shields.io/badge/Prefect-024DFD?style=flat&logo=prefect&logoColor=white)
![Fivetran](https://img.shields.io/badge/Fivetran-0073E6?style=flat&logo=fivetran&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![Teradata](https://img.shields.io/badge/Teradata-F37440?style=flat&logo=teradata&logoColor=white)

**Cloud & MLOps:**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**ML & Analytics:**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)

---

## 📈 GitHub Activity

<p align="center">
  <img src="./profile/stats.svg" alt="GitHub stats" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph-black.vercel.app/graph?username=OmaryElkady&theme=tokyo-night&hide_border=true&area=true&area_color=70a5fd&custom_title=Contributions%20(last%2031%20days)" width="95%" alt="Contribution graph" />
</p>

<sub>Stats card is regenerated daily by a <a href=".github/workflows/readme-cards.yml">GitHub Action</a>. Most of my day-to-day work at Delta lives in private enterprise repos.</sub>
