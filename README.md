# IDX-Exchange-Data-Analyst-Project

## Overview
A 12-week data analyst internship at IDX Exchange, analyzing real MLS 
transaction data to generate actionable housing market intelligence.  
Tools: **Python (Pandas)** · **Tableau Desktop** · **CoreLogic Trestle API**

---

## Project Phases & Progress

| Phase | Weeks | Description | Status |
|-------|-------|-------------|--------|
| Orientation | Week 0 | MLS data pipeline & API setup
| Dataset Aggregation | Week 1 | Concatenate monthly MLS CSVs
| Structuring & Validation | Weeks 2–3 | EDA, missing value analysis, mortgage rate enrichment 
| Data Cleaning | Weeks 4–5 | Date formatting, outlier flagging, geo validation 
| Feature Engineering | Week 6 | Market metrics, school district join 
| Outlier Detection | Week 7 | IQR filtering, analysis-ready dataset 
| Tableau Dashboards | Weeks 8–10 | Market & competitive intelligence dashboards 
| Final Presentation | Weeks 11–12 | Report + live presentation

---

## Key Metrics Engineered
- **Price Ratio** – ClosePrice / OriginalListPrice
- **Price Per Sq Ft** – ClosePrice / LivingArea
- **Days on Market** – Time-to-sell indicator
- **Listing-to-Contract Days** – Speed of offer acceptance
- **Contract-to-Close Days** – Escrow duration
- **Close-to-Original-List Ratio** – Full price reduction history

---

## Tech Stack
| Tool | Purpose |
|------|---------|
| Python 3 + Pandas | Data cleaning, EDA, feature engineering |
| Tableau Desktop Public | Interactive dashboard development |
| CoreLogic Trestle API | MLS data source |
| FRED API (St. Louis Fed) | 30-year mortgage rate enrichment |
| GitHub | Version control |

---

## Deliverables
- [ ] Week 1 – Combined MLS dataset (.py script)
- [ ] Weeks 2–3 – EDA report + mortgage rate enrichment script
- [ ] Weeks 4–5 – Cleaned analysis-ready CSV + transformation script
- [ ] Week 6 – Feature engineering script + segmented summary
- [ ] Week 7 – IQR outlier detection script + filtered dataset
- [ ] Weeks 8–10 – `market_analysis.twbx` + `competitive_analysis.twbx`
- [ ] Weeks 11–12 – 1-Page Market Intelligence Report + Tableau Public links

---

## Tableau Dashboards (Published)
> Links will be updated as dashboards are published to Tableau Public

- Market Analysis Dashboard: *(coming soon)*
- Competitive Analysis Dashboard: *(coming soon)*

---

## Project Structure
```
IDX-Exchange-Data-Analyst-Project/
├── notebooks/
│   ├── week1_aggregation.py
│   ├── week2_3_eda_mortgage.py
│   ├── week4_5_cleaning.py
│   ├── week6_feature_engineering.py
│   └── week7_outlier_detection.py
│
├── dashboards/
│   ├── market_analysis.twbx
│   └── competitive_analysis.twbx
│
├── reports/
│   └── market_intelligence_report.pdf
│
├── data/               # ⚠️ Excluded – confidential MLS data
└── README.md
```
---

## Data Confidentiality Notice
All MLS datasets used in this project are sourced from live transaction 
records provided by IDX Exchange. Raw data files are excluded from this 
repository and are not distributed externally.

---

## Author
**Qianyu Lu**  
Data Analyst Intern @ IDX Exchange  
https://www.linkedin.com/in/qianyu-lu/ 
