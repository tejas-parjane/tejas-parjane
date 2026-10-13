# Tejas Parjane <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">

[![GitHub Tejas Parjane](https://img.shields.io/github/followers/tejas-parjane?label=follow&style=social)](https://github.com/tejas-parjane)
[![Linkedin: Tejas Parjane](https://img.shields.io/badge/-tejas%20parjane-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tejas-parjane/)](https://www.linkedin.com/in/tejas-parjane/)
[![Twitter: Tejas Parjane](https://img.shields.io/twitter/follow/tejas_parjane?style=social)](https://twitter.com/tejas_parjane)

## Data Scientist | Machine Learning | Applied AI

Data Scientist with 3+ years of experience across analytics, machine learning, forecasting, and AI applications. Skilled in Python, SQL, statistical modeling, predictive analytics, and model evaluation, with hands-on experience building end-to-end ML systems and deploying models using FastAPI.

**What I do:** build predictive models, evaluate them honestly, and turn them into decision systems — not dashboards alone.

- **Predictive modeling** — churn / retention classification (Scikit-learn, XGBoost), time-series forecasting (ARIMA, ETS, XGBoost)
- **Model evaluation** — chronological / expanding-window validation, ROC-AUC, PR-AUC, sMAPE, calibration; no random-split leakage
- **Feature engineering** — leakage-safe rolling windows, lag / calendar features, statistical analysis with Pandas
- **Deployment fundamentals** — FastAPI model-serving APIs, Streamlit demos, Docker, reproducible training scripts + tests

> **Independent Data Science Projects | Apr 2026 – Present**
>
> The projects below are independent, self-directed ML work (synthetic or public datasets, documented methodology, reproducible code).
> They are labeled as independent projects — not freelance client engagements.

---

## Selected work (independent Data Science projects)

### 1. [attention-os](https://github.com/tejas-parjane/attention-os) — Predictive ML decision system
End-to-end retention + monetization modeling: leakage-safe features (40 cols) → Logistic / Random Forest / XGBoost on a chronological 70/15/15 split (best by ROC-AUC) → deterministic decision engine with guardrails → FastAPI + experiment framework (Welch's t-test).
- Retention ROC-AUC **0.84**, Monetization ROC-AUC **0.89** (held-out chronological test set, synthetic data — see repo for full tables)
- Python, Pandas, Scikit-learn, XGBoost, FastAPI, Streamlit

### 2. [forecasting-engine](https://github.com/tejas-parjane/forecasting-engine) — Time-series forecasting with honest validation
Validate → explore → expanding-window backtest → select → forecast with uncertainty → explain → recommend. Naive / Seasonal-Naive / ETS / ARIMA / XGBoost, ranked by backtested sMAPE.
- Model chosen on validation folds only; prediction intervals widen with horizon; drivers reported as association, never causality
- Python, statsmodels, XGBoost, FastAPI, Streamlit

### 3. [growth-decision-engine](https://github.com/tejas-parjane/growth-decision-engine) — Churn prediction → next-best-action API
RandomForest (250 trees, class-balanced) + StandardScaler pipeline on engineered customer features, stratified train/test split, ROC-AUC / average-precision evaluation; rules layer converts churn probability + customer value into an explainable action served via FastAPI.
- Python, Scikit-learn, Pandas, FastAPI, Streamlit

### Applied AI (complements core ML work)
- **[business-intelligent-rag-agent](https://github.com/tejas-parjane/business-intelligent-rag-agent)** — evidence-first BI RAG agent: LangChain, governed SQL (no generated-SQL execution), citations, evaluation, FastAPI. Demonstrates applied-AI engineering alongside traditional ML.

Live demos (where available) are linked inside each repo. All metrics are measured on the project's own synthetic/demo data — see each README's *Limitations* section.

---

## Tech stack (focused)

### Core Data Science
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-6E7681)
![statsmodels](https://img.shields.io/badge/statsmodels-6E7681)
![SHAP](https://img.shields.io/badge/SHAP-6E7681)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?logo=jupyter&logoColor=white)

### Model serving & reproducibility
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-3B82F6)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-0B6B5C?logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-6E7681)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white)

### Also used (secondary)
![LangChain](https://img.shields.io/badge/LangChain-6E7681)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)

---

## How I work (what recruiters can verify in every repo)

1. **Methodology first** — target definition, validation scheme, and leakage prevention stated up front.
2. **Evaluation with context** — ROC-AUC / PR-AUC / precision / recall / calibration for classification; MAE / RMSE / sMAPE / WAPE with caveats for forecasting.
3. **Reproducible** — pinned dependencies, fixed seeds, one-command training scripts, tests.
4. **Honest limitations** — synthetic-data scope, correlational (not causal) predictions, and what would change with real data.

## Background
- Analytics experience (TSL Consultancy) + independent ML / forecasting / decision-system projects.
- Open to: Associate Data Scientist · Junior Data Scientist · Applied Data Scientist · ML-focused Analyst roles.

[LinkedIn](https://www.linkedin.com/in/tejas-parjane/)
