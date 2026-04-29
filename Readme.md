# Hi, I'm Chenge Li 👋

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2196F3&center=true&vCenter=true&width=800&lines=Data+Analyst+%7C+MS+Business+Analytics;Building+End-to-End+Data+Pipelines;Translating+Data+Into+Business+Impact;Mountain+View,+CA" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/chenge-li-05009b3b2"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://public.tableau.com/app/profile/chenge.li3102/vizzes"><img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" alt="Tableau"/></a>
  <a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🚀 What I Do

I design **hybrid-architecture data systems** that combine modern ELT pipelines with intelligent analytics layers. My approach follows a core principle: **push computation upstream, deliver insight downstream.**

Instead of relying on heavy front-end calculations, I architect pipelines where Python handles ingestion, dbt structures the transformation logic in SQL, and the visualization layer renders pre-optimized data — fast, scalable, and maintainable.

> **The Philosophy:** *The intelligence lives in the pipeline, not the dashboard.*

---

## 🛠️ Tech Stack & Tools

**Languages & Databases** ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/sql-150458?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=google-cloud&logoColor=white)

**Data Engineering & ML** ![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Visualization & BI** ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Certifications & Tools** ![dbt Fundamentals](https://img.shields.io/badge/Cert-dbt_Fundamentals-FF694B?style=flat-square)
![Six Sigma Green Belt](https://img.shields.io/badge/Cert-Six_Sigma_Green_Belt-00A550?style=flat-square)
![Google Analytics](https://img.shields.io/badge/Cert-Google_Analytics-F4B400?style=flat-square)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)

---

## 📂 Featured Projects

## 🌟 Open Source Contributions

### [DATA-STACK-LAB](https://github.com/data-stack-lab/data-stack-lab)
* **Role:** Contributor (Data Quality Engineering)
* **Contribution:** Implemented automated data quality checks using **Soda Core** for dbt-based data pipelines.
* **Impact:** * Configured 10+ validation checks across `staging` and `marts` layers to ensure data integrity.
    * Established testing for row counts, primary key uniqueness, and numeric range constraints.
    * Streamlined the testing workflow by integrating Soda configurations within a Dockerized environment.
* **Tech Stack:** Soda Core · dbt · PostgreSQL · Docker
### 🏗️ Data Pipeline & Intelligent Modeling (dbt + DuckDB)

| Project | Stack | What It Demonstrates |
|---------|-------|---------------------|
| [**LLM Audit Pipeline**](https://github.com/chengelili36-max/LLMOps-Audit-System) · [Dashboard](https://public.tableau.com/app/profile/chenge.li3102/viz/Sankey_preview/Sheet1) | `Python` `dbt` `DuckDB` | Async API ingestion → dbt staging/mart → **data densification pushed into SQL layer** via `generate_series()` — eliminates Tableau table-calc overhead for continuous Sankey curve rendering. |
| [**Game Economy Pipeline**](https://github.com/chengelili36-max/looker_game_project) · [Dashboard](https://datastudio.google.com/reporting/6b3080da-dbe7-4698-8395-e1c3f1dfd406/page/y8CwF) | `Python` `dbt` `Looker` | 5,000+ daily transaction logs → star-schema dimensional model → executive KPI dashboard with Net Profit, ROI, and Hourly Wage calculations in dbt marts. |

### 📊 Advanced Tableau Engineering (Zero Plugins)

| Project | Technique | What It Demonstrates |
|---------|-----------|---------------------|
| [**Multi-Touch Attribution Sankey**](https://github.com/chengelili36-max/Advanced-Sankey-Diagram-in-Tableau-User-Acquisition-Flow) · [Live](https://public.tableau.com/app/profile/chenge.li3102/viz/SankeyDiagram_17757895174990/Dashboard1) | `Densification` `Sigmoid` | Native Sankey diagram built from first principles. Nested table calculations handle ribbon geometry at each LOD. |
| [**Call Center Command**](https://github.com/chengelili36-max/Call-Center-Dashboard) · [Live](https://public.tableau.com/app/profile/chenge.li3102/viz/US_Call_Center_Command_Dashboard/Dashboard1) | `Text Parsing` `Heatmaps` | 30,000+ unstructured logs → engineered Negative Sentiment Rate (33.58%) → heatmap-driven staffing recommendations. |
| [**Retail 360 Health Monitor**](https://github.com/chengelili36-max/retail-360-data-analysis) · [Live](https://public.tableau.com/app/profile/chenge.li3102/viz/TheRetailPulseRetailBusinessHealthMonitor/Dashboard1) | `RFM` `Bullet Graphs` | End-to-end: customer segmentation → dynamic safety-stock alerts → critical inventory breach detection. |

### 🧠 Machine Learning & Statistical Rigor

| Project | Method | Business Impact |
|---------|--------|-----------------|
| [**Churn Prediction & ROI**](https://github.com/chengelili36-max/Telco-Churn-ROI-Prediction) | `Random Forest` | Translated model output into a **$1.59M annualized ROI framework** — the bridge from AUC to P&L that most projects skip. |
| [**A/B Test — Conversion**](https://github.com/chengelili36-max/E-Commerce-AB-Testing) | `Z-Test` | p = 0.9051 — **killed a harmful landing-page rollout**. The value was saying "no" with statistical proof. |
| [**E-Commerce Retention**](https://github.com/chengelili36-max/E-Commerce-SQL-Analysis) | `SQL Window Functions`| Discovered a **79.2-day repurchase cycle** that retimed CRM email triggers from Day 30 to Day 65–75. |

---

## 🎯 Design Philosophy

1. ⚙️ **Intelligence belongs in the pipeline, not the dashboard.** Data densification and business logic live in dbt/SQL. This makes dashboards faster, pipelines testable, and logic version-controlled.
2. 📐 **Build from first principles.** Understanding the mechanics (like sigmoid math for Sankey geometry) means I can adapt the technique to any visualization challenge without relying on third-party plugins.
3. 💵 **Every model must speak in dollars.** A churn classifier with 85% precision is interesting. A churn classifier that translates to $1.59M annualized ROI is actionable. 
4. 🛡️ **Statistical rigor protects decisions.** The job of an analyst is to prevent bad decisions, not just confirm good ones.

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chengelili36-max&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&text_color=C9D1D9&icon_color=58A6FF&title_color=58A6FF" alt="GitHub Stats" />
</p>

<p align="center">
  <i>Building data systems that think. Based in Mountain View, CA.</i>
</p>
