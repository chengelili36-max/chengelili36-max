# Hi, I'm Chenge Li

**Data Analyst | MS Business Analytics**
Building end-to-end data pipelines, advanced Tableau visualizations, and machine learning models that translate into real business impact.

Mountain View, CA · [LinkedIn](https://www.linkedin.com/in/chenge-li-05009b3b2) · [Tableau Public](https://public.tableau.com/app/profile/chenge.li3102/vizzes)

---

## What I Do

I design **hybrid-architecture data systems** that combine modern ELT pipelines with intelligent analytics layers. My approach follows a core principle: **push computation upstream, deliver insight downstream.**

Instead of relying on heavy front-end calculations, I architect pipelines where Python handles ingestion, dbt structures the transformation logic in SQL, and the visualization layer (Tableau, Looker Studio) renders pre-optimized data — fast, scalable, and maintainable.

```
Raw Data → Python Ingestion → DuckDB/Snowflake → dbt (Staging → Marts) → BI Dashboard
```

Every project in my portfolio follows this philosophy: **the intelligence lives in the pipeline, not the dashboard.**

---

## Technical Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    DATA INGESTION LAYER                      │
│         Python (async API calls, web scraping, CSVs)         │
│         Pandas · NumPy · SciPy · Scikit-Learn                │
└──────────────────────┬──────────────────────────────────────┘
                       │
                       ▼
┌─────────────────────────────────────────────────────────────┐
│                   WAREHOUSE & MODELING                        │
│              DuckDB · Snowflake · BigQuery                    │
│     dbt (staging → intermediate → mart · star schema)        │
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
```

---

## Featured Projects

### Data Pipeline & Intelligent Modeling (dbt + DuckDB)

| Project | Stack | What It Demonstrates |
|---------|-------|---------------------|
| [**LLM Audit Pipeline**](https://github.com/chengelili36-max/LLMOps-Audit-System) · [Dashboard](https://public.tableau.com/app/profile/chenge.li3102/viz/Sankey_preview/Sheet1) | Python · dbt · DuckDB · Tableau | Async API ingestion → dbt staging/mart → **data densification pushed into SQL layer** via `generate_series()` — eliminates Tableau table-calc overhead for continuous Sankey curve rendering |
| [**Game Economy Pipeline**](https://github.com/chengelili36-max/looker_game_project) · [Dashboard](https://datastudio.google.com/reporting/6b3080da-dbe7-4698-8395-e1c3f1dfd406/page/y8CwF) | Python · dbt · DuckDB · Looker Studio | 5,000+ daily transaction logs → star-schema dimensional model → executive KPI dashboard with Net Profit, ROI, and Hourly Wage calculations in dbt marts |

### Advanced Tableau Engineering (Zero Plugins)

| Project | Technique | What It Demonstrates |
|---------|-----------|---------------------|
| [**Multi-Touch Attribution Sankey**](https://github.com/chengelili36-max/Advanced-Sankey-Diagram-in-Tableau-User-Acquisition-Flow) · [Live](https://public.tableau.com/app/profile/chenge.li3102/viz/SankeyDiagram_17757895174990/Dashboard1) | Data Densification (49 bins) + Sigmoid Modeling | Native Sankey diagram built from first principles — no Flourish, no plugins. Nested table calculations handle ribbon geometry at each level of detail. |
| [**Call Center Command Dashboard**](https://github.com/chengelili36-max/Call-Center-Dashboard) · [Live](https://public.tableau.com/app/profile/chenge.li3102/viz/US_Call_Center_Command_Dashboard/Dashboard1) | Text Parsing + Heatmaps | 30,000+ unstructured logs → engineered Negative Sentiment Rate (33.58%) → heatmap-driven staffing recommendations |
| [**Retail 360**](https://github.com/chengelili36-max/retail-360-data-analysis) · [Live](https://public.tableau.com/app/profile/chenge.li3102/viz/TheRetailPulseRetailBusinessHealthMonitor/Dashboard1) | RFM Segmentation + Bullet Graphs | End-to-end: customer segmentation → dynamic safety-stock alerts → critical inventory breach detection |

### Machine Learning & Statistical Rigor

| Project | Method | Business Impact |
|---------|--------|-----------------|
| [**Churn Prediction & ROI**](https://github.com/chengelili36-max/Telco-Churn-ROI-Prediction) | Random Forest (precision-optimized, balanced weights) | Translated model output into a **$1.59M annualized ROI framework** — the bridge from AUC to P&L that most ML projects skip |
| [**A/B Test — Conversion**](https://github.com/chengelili36-max/E-Commerce-AB-Testing) | Two-Proportion Z-Test on 290,000+ sessions | p = 0.9051 — **killed a harmful landing-page rollout** before global deployment. The value was saying "no" with statistical proof. |
| [**E-Commerce Retention**](https://github.com/chengelili36-max/E-Commerce-SQL-Analysis) | SQL Window Functions (LAG, PARTITION BY) on 100K+ orders | Discovered a **79.2-day repurchase cycle** that retimed CRM email triggers from Day 30 to Day 65–75 |

---

## Design Philosophy

**1. Intelligence belongs in the pipeline, not the dashboard.**
Data densification, sigmoid modeling, and business logic live in dbt/SQL — not in Tableau calculated fields. This makes dashboards faster, pipelines testable, and logic version-controlled.

**2. Build from first principles.**
The Sankey diagram uses 49 virtual bins and sigmoid math for ribbon geometry. No plugins. No Flourish. Understanding the mechanics means I can adapt the technique to any visualization challenge.

**3. Every model must speak in dollars.**
A churn classifier with 85% precision is interesting. A churn classifier that translates to $1.59M annualized ROI is actionable. I bridge model metrics to P&L impact because that's what decision-makers need.

**4. Statistical rigor protects decisions.**
The A/B test that killed a rollout (p = 0.9051) saved more value than the tests that "worked." The job of an analyst is to prevent bad decisions, not just confirm good ones.

---

## Tech Stack

```
Languages:       Python (Pandas · NumPy · SciPy · Scikit-Learn) · SQL · R
Data Modeling:    dbt (DuckDB · Snowflake) · Star Schema · Staging/Mart Architecture
Databases:        DuckDB · Snowflake · BigQuery · PostgreSQL
Visualization:    Tableau (Data Densification · Sigmoid · Sankey) · Looker Studio · Power BI
ML & Stats:       Random Forest · Clustering · Z-Tests · Cohort Analysis · RFM
Tools:            Git · Claude Code · Excel/Sheets · GA4
```

## Certifications

`dbt Fundamentals` · `Google Analytics` · `Google Looker Studio` · `HubSpot Sales Hub` · `HubSpot Inbound Marketing` · `HubSpot Reporting` · `Six Sigma Green Belt` · `Generative Deep Learning`

---

## Education

**Master of Business in Data Analytics** — University of La Verne
**Bachelor of Arts in Mathematics** — San Jose State University

---

*Building data systems that think. Based in Mountain View, CA.*
