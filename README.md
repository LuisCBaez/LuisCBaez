# Luis C. Baez

**Machine Learning Engineer**

I build forecasting and machine-learning systems for real operational settings, where the hard part is rarely just choosing a model. The harder work is understanding the decision being supported, preparing unreliable data, designing evaluation around real failure modes, and making the workflow reproducible enough for others to trust and operate.

My background is in civil, geotechnical, and geo-energy engineering. Before moving into ML, I worked with physical systems where uncertainty, incomplete measurements, and practical constraints were part of the job. That experience still shapes how I build models: start from the problem, test simple baselines, look for leakage and bias, and add complexity only when it improves the decision.

My current focus is forecasting and production-oriented ML: time-aware validation, reproducible pipelines, experiment tracking, model comparison, documentation, and handover.

I am especially interested in applied ML/AI systems for industrial, energy, life-sciences, scientific, and other data-intensive domains

---

## Projects

### [tetouan-power-mlops](https://github.com/LuisCBaez/tetouan-power-mlops) — flagship · in active development

End-to-end electricity-consumption forecasting on public 10-minute data from Tetouan, Morocco — built as a production-oriented MLOps project, not a notebook.

- Time-aware splitting and leakage-safe evaluation
- Reusable, tested Python package with typed (Pydantic) configuration
- `pytest`, Ruff, and pre-commit, with PR-gated GitHub Actions CI on a protected `main`
- Databricks workflows with Unity Catalog and MLflow experiment tracking
- Databricks Asset Bundles for deployment-oriented structure
- **Next:** feature engineering, batch inference, serving, monitoring, and retraining

`Python` · `LightGBM` · `Databricks` · `MLflow` · `Unity Catalog` · `AWS S3/IAM` · `pytest` · `GitHub Actions`

### [well-log-ml](https://github.com/LuisCBaez/well-log-ml) — applied geoscience ML

Supporting ML framework for the machine-learning/property-prediction part of a TU Delft doctoral research project on Dutch geothermal plays. Combined laboratory measurements with depth-indexed well logs to predict geothermal rock properties. [TU Delft repository](https://repository.tudelft.nl/record/uuid:8efba807-22a3-4f9f-b73e-5afbce251966)

- Built preprocessing workflows for well-log standardization, lab-log merging, PCHIP interpolation, and exploratory analysis
- Compared Ridge Regression, Random Forest, LightGBM, and XGBoost with GridSearch and Optuna tuning
- Used well-based validation with GroupKFold to reduce leakage risk in a limited-well dataset
- Documented residuals, bias, feature importance, and limits around small data and no external blind-well test

`Python` · `scikit-learn` · `LightGBM` · `XGBoost` · `Optuna`

### [applied-time-series](https://github.com/LuisCBaez/applied-time-series) — forecasting methods

End-to-end forecasting project comparing seasonal-naïve, AutoARIMA, and feature-based LightGBM (MLForecast) under chronological holdout evaluation across error and bias metrics.

`StatsForecast` · `MLForecast` · `LightGBM`

### [MSc thesis — predicting missing well logs](https://github.com/LuisCBaez/Predicting_Well_logs_MICE_TUDelft_Msc_Thesis)

Published TU Delft research on MICE-based well-log imputation (XGBoost, Random Forest, KNN, Bayesian Ridge) across geological datasets, documenting how data quality and geological heterogeneity drive imputation accuracy. [Read it on the TU Delft repository.](https://repository.tudelft.nl/record/uuid:873cc936-d799-40c6-97d5-b168012ad090)

---

## Core stack

| Area | Tools |
|---|---|
| Languages | Python, SQL, Bash |
| ML & forecasting | scikit-learn, LightGBM, XGBoost, statsmodels, StatsForecast, MLForecast |
| ML systems | Databricks, MLflow, Delta Lake, Unity Catalog, AWS S3/IAM |
| Engineering | pytest, Ruff, pre-commit, Pydantic, uv, GitHub Actions |
| Delivery | Streamlit, Power BI |
| Learning now | PyTorch, deep-learning forecasting |

---

## Currently

- Extending `tetouan-power-mlops` toward serving, monitoring, and retraining
- Deepening time-series forecasting and deep-learning foundations
- Learning German

---

## Background

- 🎓 **MSc Applied Earth Sciences (Geo-Energy)** — TU Delft
- 🎓 **BSc Civil Engineering** — Pontificia Universidad Javeriana
- 💻 2019–2021: self-directed transition into ML (Stanford ML, MITx Probability, IBM Data Science), continued while relocating internationally, before the MSc at TU Delft
- Civil & geotechnical engineering (tunnels, foundations, slopes, excavations) before moving into applied ML across forecasting, geoscience, and energy data
- Spanish (native) · English (professional) · German (in progress)

---

## Connect

[LinkedIn](https://www.linkedin.com/in/luiscbaezl/) · [Repositories](https://github.com/LuisCBaez?tab=repositories)

---

**Engineering judgment applied to real-world AI and machine-learning systems.**
