
# 🛡️ Cyber Threat Intelligence Pipeline (Databricks Project)

## 🎯 Project Overview
This project simulates a real-world scenario where cyber threat data is ingested, cleaned, enriched, and analyzed using Databricks (SQL, Python, PySpark, Delta Lake). Ideal for data engineers looking to practice real-time analytics, data lake management, and dashboarding in a secure or government-focused context.

---

## 🗂️ Project Structure

```
Cyber_Threat_Intelligence_Pipeline/
│
├── notebooks/
│   ├── 01_ingest_threat_data.py
│   ├── 02_transform_clean_delta.py
│   ├── 03_enrich_and_aggregate.py
│   └── 04_visualize_and_dashboard.py
│
├── data_sources.md
├── README.md
```

---

## 🧰 Technologies Used
- Databricks (Community or Azure)
- Apache Spark / PySpark
- Delta Lake
- Databricks SQL
- Git + GitHub

---

## 📊 Sample Data Sources
- AbuseIPDB: https://www.abuseipdb.com/
- AlienVault OTX: https://otx.alienvault.com/
- Databricks Sample Datasets: `/databricks-datasets`

---

## 🧪 Learning Objectives
- Use PySpark to read and clean CSV/JSON feeds
- Write Delta Lake tables for high-performance analytics
- Perform data enrichment via joins and UDFs
- Create interactive dashboards using Databricks SQL
- Schedule and automate data jobs using Databricks Workflows
- Use GitHub for source control

---

## 🚀 Getting Started
1. Import the notebooks into your Databricks workspace.
2. Create a cluster (DBR 13+ recommended).
3. Load data sources into `/FileStore` or via Auto Loader.
4. Run each notebook step-by-step to complete the pipeline.
5. Publish your dashboard and set up Job scheduling.

---

## 👨‍💻 Author
Nathaniel Landry Jr. — [natlandryent@yahoo.com](mailto:natlandryent@yahoo.com)
