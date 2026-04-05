# 🏥 Global Healthcare Expenditure Analysis
### Identifying Cost Drivers and Optimization Opportunities in Global Health Spending
 
---
 
## Project Overview
 
Healthcare systems worldwide face mounting pressure to allocate resources efficiently. Inefficient spending leads to higher taxes, increased out-of-pocket costs, and unequal access to medical services. This project uses historical healthcare expenditure data to identify the features and variables most strongly associated with high spending — and to surface actionable opportunities for cost reduction without compromising patient outcomes.
 
The analysis draws on the **WHO Global Health Expenditure Database (GHED)**, a longitudinal dataset covering ~190 countries from 2000–2023, with over 700 indicators spanning financing sources, health functions, disease categories, and provider types.
 
---
 
## Problem Statement
 
The US healthcare market exceeded **$5.3 trillion in 2024** and is projected to grow to $5.6 trillion by 2025 (CMS). Despite this scale, the US consistently spends more than peer countries while achieving similar or worse outcomes. Key underperformers include:
 
- High administrative overhead that does not improve patient outcomes
- Overutilization of procedures, tests, and ER visits
- Managed care sub-industry inefficiencies
- Policy uncertainty and supply shortages (onset ~late 2020)
 
This project aims to identify which expenditure variables drive cost inflation and which interventions — such as increased preventive care and streamlined billing — offer the most viable path to a **5–15% reduction in healthcare spending**.
 
---
 
## Goals
 
| # | Goal |
|---|------|
| 1 | Conduct a full exploratory data analysis (EDA) of the GHED dataset |
| 2 | Identify leading cost drivers across countries, regions, and income groups |
| 3 | Examine the relationship between spending patterns and health outcomes |
| 4 | Build predictive models to forecast expenditure trends |
| 5 | Segment countries/regions to surface comparative insights |
| 6 | Deliver actionable findings for hospital administrators, policymakers, and insurers |
 
---
 
## Dataset
 
**Source:** [WHO Global Health Expenditure Database (GHED)](https://apps.who.int/nha/database)  
**Last Updated:** December 12, 2025  
**Coverage:** ~190 countries, 2000–2023 (2024 data preliminary)  
**Size:** ~4,600 rows × 700+ columns
 
### Key variable groups
 
| Prefix | Description |
|--------|-------------|
| `che_*` | Current health expenditure (total, per capita, % of GDP) |
| `gghed_*` | Government/compulsory health spending |
| `pvtd_*` | Private/voluntary health spending |
| `oops_*` | Out-of-pocket spending |
| `ext_*` | External/donor financing |
| `hf_*` | Financing scheme breakdowns |
| `hc_*` | Health function (curative, preventive, etc.) |
| `dis_*` | Disease category spending |
| `hp_*` | Health provider type |
| `phc_*` | Primary health care |
 
> **Note:** Many columns have high missingness rates. EDA will include a full coverage audit before modeling begins.
