# survival_analysis_ma# 📊 Telco Churn Survival Analysis

This project applies **Survival Analysis** using **Accelerated Failure Time (AFT)** models to analyze and predict customer churn behavior in a telecommunications dataset. It also estimates **Customer Lifetime Value (CLV)** to identify high-value customer segments and inform retention strategies.

## 🔧 Methods

- Preprocessing and encoding categorical variables
- Fitting AFT models:
  - Weibull AFT
  - LogNormal AFT
  - LogLogistic AFT
- Model comparison using AIC, concordance, and interpretability
- Selection of significant predictors
- CLV calculation based on predicted lifetimes and income
- Segment-level CLV insights and churn risk assessment

## 📈 Key Findings

- **LogNormal AFT** provided the best fit based on AIC.
- Key churn predictors: internet/voice services, age, marital status, customer type.
- CLV is highly skewed — small segments drive most of the value.
- A 5% retention budget targeted at at-risk, high-CLV customers is recommended.

## 📁 Files

- `survival_analysis.ipynb` — Full notebook with model fitting, CLV computation, and visualizations
- `requirements.txt` — Python dependencies
- `README.md` — Project overview
- `report.pdf` (optional) — Formal write-up of analysis and recommendations

## 📌 Requirements

```bash
pip install -r requirements.txt