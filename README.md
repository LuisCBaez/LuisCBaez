# Luis C. Baez

**Machine Learning Engineer**

Machine Learning Engineer with an engineering background, focused on forecasting, applied ML, and production-oriented ML workflows for real operational and scientific domains.

I build forecasting and machine-learning systems for real operational settings, where the hard part is rarely just choosing a model. The harder work is understanding the decision being supported, preparing unreliable data, designing evaluation around real failure modes, and making the workflow reproducible enough for others to trust and operate.

My background is in civil, geotechnical, and geo-energy engineering. Before moving into ML, I worked with physical systems where uncertainty, incomplete measurements, and practical constraints were part of the job. That experience still shapes how I build models: start from the problem, test simple baselines, look for leakage and bias, and add complexity only when it improves the decision.

My current focus is forecasting and production-oriented ML: time-aware validation, reproducible pipelines, experiment tracking, model comparison, clear documentation, and user enablement.

I am especially interested in applied ML/AI systems for industrial, energy, life-sciences, scientific, and other data-intensive domains

---

## Projects

### [tetouan-power-mlops](https://github.com/LuisCBaez/tetouan-power-mlops) — flagship · in active development

End-to-end MLOps system for power-consumption prediction on public 10-minute data from Tetouan, Morocco — built as a production-oriented project, not a notebook.

- Reusable, tested Python package with typed (Pydantic) configuration
- `pytest`, Ruff, and pre-commit, with PR-gated GitHub Actions CI on a protected `main`
- Databricks Asset Bundle with Unity Catalog tables and MLflow experiment tracking; pipeline scripts executed on Databricks
- **Next:** feature engineering, batch inference, serving, monitoring, and retraining

`Python` | `LightGBM` | `Databricks` | `MLflow` | `Unity Catalog` | `AWS S3/IAM` | `pytest` | `GitHub Actions`

### [demand-forecasting-system-design](https://github.com/LuisCBaez/demand-forecasting-system-design) — demand-planning system design

Methodology case study on designing, evaluating, and evolving a transparent monthly demand-forecasting workflow. Documents architecture, demand profiling, profile-aware model competition, chronological evaluation, and handover — using diagrams and pseudocode because client code and data cannot be shared.

- Standardized business inputs into monthly modeling histories and reporting datasets
- Profile-aware competition across baselines, statistical, intermittent-demand, and LightGBM methods
- Time-aware validation, MLflow tracking, forecast guardrails, and aggregate-to-detail allocation
- Retrospective evaluation across historical forecast origins and multiple horizons

Client code, data, configurations, identifying details, and results remain private.

`Python` | `Databricks` | `MLflow` | `StatsForecast` | `MLForecast` | `LightGBM` | `Optuna` | `Power BI` | `Streamlit`

### [well-log-ml](https://github.com/LuisCBaez/well-log-ml) — applied geoscience ML

Supporting ML framework for the machine-learning/property-prediction part of a TU Delft doctoral research project on Dutch geothermal plays. Combined laboratory measurements with depth-indexed well logs to predict geothermal rock properties. [TU Delft repository](https://repository.tudelft.nl/record/uuid:8efba807-22a3-4f9f-b73e-5afbce251966)

- Built preprocessing workflows for well-log standardization, lab-log merging, PCHIP interpolation, and exploratory analysis
- Compared Ridge Regression, Random Forest, LightGBM, and XGBoost with GridSearch and Optuna tuning
- Used well-based validation with GroupKFold to reduce leakage risk in a limited-well dataset
- Documented residuals, bias, feature importance, and limits around small data and no external blind-well test

`Python` | `scikit-learn` | `LightGBM` | `XGBoost` | `Optuna`

### [MSc thesis — predicting missing well logs](https://github.com/LuisCBaez/Predicting_Well_logs_MICE_TUDelft_Msc_Thesis)

Published TU Delft research on MICE-based well-log imputation (XGBoost, Random Forest, KNN, Bayesian Ridge) across geological datasets, documenting how data quality and geological heterogeneity drive imputation accuracy. [Read it on the TU Delft repository.](https://repository.tudelft.nl/record/uuid:873cc936-d799-40c6-97d5-b168012ad090)

`Python` | `scikit-learn` | `XGBoost` | `Random Forest` | `KNN` | `Bayesian Ridge` | `MICE`

---

## Core stack

| Area | Tools |
|---|---|
| Languages | Python, SQL, Bash |
| ML & forecasting | scikit-learn, LightGBM, XGBoost, statsmodels, StatsForecast, MLForecast |
| ML systems | Databricks, MLflow, Delta Lake, Unity Catalog|
| Engineering | pytest, Ruff, pre-commit, Pydantic, uv, GitHub Actions |
| Delivery | Streamlit, Power BI |
| Learning now | PyTorch, deep-learning forecasting |

---

## Background

- 🎓 **MSc Applied Earth Sciences (Geo-Energy)** — TU Delft
- 🎓 **BSc Civil Engineering** — Pontificia Universidad Javeriana
- 💻 2019–2021: self-directed transition into ML (Stanford ML, MITx Probability, IBM Data Science), continued while relocating internationally, before the MSc at TU Delft
- Civil & geotechnical engineering (tunnels, foundations, slopes, excavations) before moving into applied ML across forecasting, geoscience, and energy data
- Spanish (native) · English (professional) · German (A1.2, actively developing)

---

## Connect

[LinkedIn](https://www.linkedin.com/in/luiscbaezl/) | [Repositories](https://github.com/LuisCBaez?tab=repositories)

---

**Engineering judgment applied to real-world AI and machine-learning systems.**
