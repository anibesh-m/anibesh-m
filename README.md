# 🚀 Analytics Engineering Portfolio

Welcome!  
This repository showcases hands-on analytics engineering work focused on building reliable, automated, and cost-efficient data pipelines using modern cloud tooling — especially Google Cloud Platform.

The goal is to demonstrate **real-world patterns**, including orchestration, SQL modeling, cloud workflows, optimization examples, and BI reporting logic.

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anibeshm7&color=blueviolet&style=flat" />
</p>

---

## ⏰ Live Time

![Time](https://img.shields.io/badge/dynamic/json?url=https://worldtimeapi.org/api/timezone/Asia/Kolkata&query=datetime&label=IST%20Time&color=blue)

---

## 🧰 Tech Stack

| Category | Tools |
|---------|-------|
| Cloud | Google Cloud Platform |
| Orchestration | Apache Airflow / Cloud Composer |
| Processing | Python |
| Data Warehouse | BigQuery |
| Analytics Layer | Looker, Tableau |
| Querying | SQL (BigQuery SQL) |
| CI/CD & Best Practices | Testing, linting, governance coming soon |

<p>
  <img src="https://img.shields.io/badge/GCP-BigQuery-blue" />
  <img src="https://img.shields.io/badge/Python-3.10-yellow" />
  <img src="https://img.shields.io/badge/Airflow-Orchestration-green" />
  <img src="https://img.shields.io/badge/SQL-Analytics-orange" />
  <img src="https://img.shields.io/badge/Tableau-Dashboards-blueviolet" />
  <img src="https://img.shields.io/badge/Looker-SemanticModeling-lightgrey" />
  <img src="https://img.shields.io/badge/AWS-CCP-red" />
</p>

---

## ☁️ High-Level Data Flow

```mermaid
graph LR
A[Raw Data Sources] --> B[GCS Landing Zone]
B --> C[Python Processing & Validation]
C --> D[Airflow Scheduling & Automation]
D --> E[BigQuery Transformations & Modeling]
E --> F[Analytics Layer / Semantic Models]
F --> G[Looker / Tableau Dashboards]
