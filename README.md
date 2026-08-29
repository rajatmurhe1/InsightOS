Markdown
# 📊 InsightOS: Enterprise Data & AI Pipeline

An end-to-end data analytics and artificial intelligence pipeline built to process raw retail transactions and generate automated business intelligence.

This project tackles the complex challenge of big data observability by connecting a **PostgreSQL Data Warehouse** directly with an **Isolation Forest Machine Learning Model**. By integrating **Advanced SQL Analytics**, **Scikit-Learn Anomaly Detection**, and an **Automated GenAI Reporting Engine**, this platform delivers a comprehensive, intelligent, and highly responsive retail monitoring system.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

---

## 🖥️ Live Executive Dashboard

> *Time-series revenue tracking, statistical anomaly detection, and RFM (Recency, Frequency, Monetary) customer segmentation.*

**🔗 [Click Here to View the Interactive Tableau Public Dashboard](https://public.tableau.com/app/profile/rajat.murhe/viz/InsightOSExecutiveDashboard/Dashboard1)**

[![InsightOS Dashboard](data/dashboard/visual.png)](https://public.tableau.com/app/profile/rajat.murhe/viz/InsightOSExecutiveDashboard/Dashboard1)


---

## Architecture & Features
* **Data Warehouse & ETL:** Scalable ingestion of multi-million transaction records into PostgreSQL with automated data normalization.
* **SQL Analytics Layer:** Advanced SQL queries (CTEs, Window Functions) calculating RFM customer segmentation and core executive KPIs.
* **AI Anomaly Detection:** Scikit-Learn `IsolationForest` model identifying statistically anomalous revenue days (sudden drops/system glitches vs. extreme volume spikes).
* **GenAI Explainability Pipeline:** Automated context formatting engine that prepares ML anomaly outputs into structured prompts for Large Language Model reporting.
* **Visual Intelligence:** Tableau dashboard tracking executive KPIs, RFM spend distributions, and longitudinal revenue trends.

## Repository Structure
```text
InsightOS/
├── .gitignore
├── README.md
├── requirements.txt
├── export_trend.py
├── llm_executive_prompt.txt
├── data/
│   ├── raw/
│   └── dashboard/
│       ├── customer_rfm.csv
│       ├── daily_sales.csv
│       ├── kpis_executive.csv
│       └── visual.png
└── src/
    ├── pipeline/
    └── anomaly/
        ├── sales_anomaly.py
        └── llm_alert.py


