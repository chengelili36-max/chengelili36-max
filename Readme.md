# Hi, I'm Chenge Li 👋

<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2196F3&center=true&vCenter=true&width=800&lines=Data+Analyst+%7C+MS+Business+Analytics;Building+End-to-End+Data+Pipelines;Translating+Data+Into+Business+Impact;Mountain+View,+CA" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/chenge-li-05009b3b2"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://public.tableau.com/app/profile/chenge.li3102/vizzes"><img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" alt="Tableau"/></a>
  <a href="mailto:chenge.li@example.com"><img src="https://img.shields.io/badge/Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 🚀 Professional Summary

I design **hybrid-architecture data systems** that merge modern ELT pipelines with intelligent analytics layers. My guiding principle is to **push computation upstream and deliver insight downstream.** By architecting pipelines where `Python` handles ingestion and `dbt` modularizes transformation logic in `SQL`, I ensure the visualization layer (Tableau, Looker Studio) renders pre-optimized data—achieving a system that is performant, scalable, and fully version-controlled.

---

## 🏛️ Technical Architecture

```text
┌─────────────────────────────────────────────────────────────┐
│                    DATA INGESTION LAYER                      │
│         Python (Async API, Web Scraping, CSV/JSON)           │
│         Pandas · NumPy · SciPy · Scikit-Learn                │
└──────────────────────┬──────────────────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────────────────┐
│                   WAREHOUSE & MODELING                        │
│              DuckDB · Snowflake · BigQuery                    │
│     dbt (Staging → Intermediate → Mart · Star Schema)        │
│         Data densification via generate_series()              │
│              Tests · Documentation · Version control          │
└──────────────────────┬──────────────────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────────────────┐
│                  ANALYTICS & ML LAYER                         │
│     Classification (Random Forest · XGBoost)                  │
│     Statistical Testing (Z-tests · Hypothesis Testing)       │
│     Cohort Analysis · RFM Segmentation · Time Series          │
└──────────────────────┬──────────────────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────────────────┐
│                  VISUALIZATION LAYER                          │
│         Tableau (Sankey · Sigmoid · Data Densification)       │
│         Looker Studio · Power BI                              │
│         Native builds — zero third-party plugins              │
└─────────────────────────────────────────────────────────────┘

---
## 🛠️ Tech Stack & Tools

| Category | Technologies |
| :--- | :--- |
| **Languages & DBs** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![SQL](https://img.shields.io/badge/sql-150458?style=flat-square&logo=postgresql&logoColor=white) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=flat-square&logo=r&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) |
| **Data Engineering** | ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat-square&logo=numpy&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=Apache%20Airflow&logoColor=white) |
| **Analytics & ML** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=Tableau&logoColor=white) ![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=google&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat-square&logo=scikit-learn&logoColor=white) |
| **Certifications** | `dbt Fundamentals` · `Six Sigma Green Belt` · `Google Analytics` · `Generative Deep Learning` |

---

## 🌟 Open Source Contributions

> ### [**Data-Stack-Lab | Soda Core Integration**](https://github.com/kiyeonjeon21/data-stack-lab/pull/19)
> *Automating data quality observability within the dbt transformation layer.*
> * **Contribution:** Developed 10+ validation checks (uniqueness, nullability, numeric ranges) for `staging` and `marts` models.
> * **Impact:** Established a robust testing framework to prevent data drift and ensure downstream dashboard accuracy.
> * **Tech Stack:** `Soda Core` · `dbt` · `PostgreSQL` · `Docker Compose`

---

## 📂 Featured Projects

### 🏗️ Data Engineering & Intelligent Modeling
| Project | Stack | Key Achievement |
| :--- | :--- | :--- |
| [**LLM Audit Pipeline**](https://github.com/chengelili36-max/LLMOps-Audit-System) | `Python` `dbt` `DuckDB` | Built async API ingestion with **SQL-layer data densification** via `generate_series()` for seamless Sankey rendering. |
| [**Game Economy Pipeline**](https://github.com/chengelili36-max/looker_game_project) | `Python` `dbt` `Looker` | Modeled 5,000+ daily logs into a **Star-Schema** to drive ROI and Net Profit KPI reporting. |

### 📊 Visualization & Statistical Rigor
| Project | Methodology | Business Impact |
| :--- | :--- | :--- |
| [**Multi-Touch Sankey**](https://github.com/chengelili36-max/Advanced-Sankey-Diagram-in-Tableau-User-Acquisition-Flow) | `Sigmoid Math` `Tableau` | Native Sankey built from first principles (49 bins) without third-party plugins. |
| [**Churn Prediction ROI**](https://github.com/chengelili36-max/Telco-Churn-ROI-Prediction) | `Random Forest` `ML` | Translated 85% precision into a **$1.59M annualized ROI framework** for P&L stakeholders. |
| [**A/B Conversion Test**](https://github.com/chengelili36-max/E-Commerce-AB-Testing) | `Z-Test` `Statistics` | Leveraged statistical proof ($p=0.9051$) to **halt a harmful rollout**, protecting global conversion. |

---

## 🎓 Education

* **Master of Science in Data Analytics** — University of La Verne
* **Bachelor of Arts in Mathematics** — San Jose State University (SJSU)

---

---

## 📈 Technical Vitality

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chengelili36-max&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&text_color=C9D1D9&icon_color=58A6FF&title_color=58A6FF" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chengelili36-max&theme=radical&hide_border=true&background=0D1117" />
</p>

<p align="center">
  <i>Building data systems that think. Based in Mountain View, CA.</i>
</p>
