# Hi, I'm Mateus Pavan
Data Scientist | Machine Learning · Time Series · Credit Risk | Python · SQL

## About Me
I'm transitioning into Data Science from 5+ years in enterprise IT (SAP consulting on international projects), bringing a background in business systems, databases, and programming logic. I hold a DataCamp Data Scientist certification and build end-to-end projects — from exploratory analysis to production-oriented modeling and monitoring — always framed around a business decision: profit, cost, risk.

Open to all formats of work (including on-site) as full-time or contractor, in national and international opportunities.

## Tools & Technologies
**Languages:** Python, SQL (MySQL, PostgreSQL, ABAP SQL)
**ML & Modeling:** Scikit-learn, XGBoost, SHAP, statsmodels (SARIMA), Prophet, PyTorch, foundation models (Chronos-2)
**Time Series:** walk-forward validation, day-ahead forecasting, leakage control
**Data & Viz:** Pandas, NumPy, Matplotlib, Seaborn, Power BI (DAX)
**MLOps & Monitoring:** PSI drift detection, model stability monitoring, FastAPI serving, Docker, GitHub Actions CI, GitHub Pages deployment
**Tools:** Jupyter, Git, GitHub
**Cloud (fundamentals):** Azure (AZ-900 track), AWS, GCP

## Featured Projects
| Project | Description | Tech |
|---|---|---|
| [Electricity Load Forecasting (ONS)](https://github.com/MateusFPavan/ons-carga-eda) | Day-ahead hourly load forecasting for Brazil's SE/CO grid. A zero-shot foundation model (Chronos-2) beats tuned SARIMA/Prophet — MASE 0.44 vs 1.27 — cutting the modeled dispatch cost of forecast error by ~65%. Walk-forward validation, leakage tests, cost-weighted evaluation. | Python, PyTorch, Chronos-2, statsmodels, Prophet, Time Series |
| [Credit Default Prediction (Lending Club)](https://github.com/MateusFPavan/credit-default-prediction-lendingclub) · **[live dashboard ▶](https://mateusfpavan.github.io/credit-default-prediction-lendingclub/)** | End-to-end credit risk model on ~673K P2P loans, optimized for portfolio profit rather than accuracy. Temporal validation, SHAP explainability, leakage screening on three fronts, and PSI drift monitoring. Served through a FastAPI scoring API, containerized with Docker and smoke-tested in GitHub Actions CI on every push. Ships with an interactive dashboard (Power BI + web) whose live threshold slider recomputes profit and the confusion matrix on the 2015 test set. | Python, XGBoost, SHAP, PSI, FastAPI, Docker, CI, Power BI |
| [Brazilian Aviation Delays EDA (ANAC)](https://github.com/MateusFPavan/anac-voos-eda) | Exploratory analysis of 876K official flight records; found delays rose 58% in 2022, tracking capacity growth rather than seasonality. Corrected a real data anomaly along the way. | Python, Pandas, EDA |

## Data Essays
Short analytical writing, published on LinkedIn with reproducible code here on GitHub. Different from the modeling projects above: the focus is the question and the read of the evidence, and the model stays deliberately simple.

| Essay | What it does | Tech |
|---|---|---|
| [What keeps a team together, and does AI quietly remove it?](https://github.com/MateusFPavan/team-cohesion-turnover-analysis) | Re-analysis of a public open-source turnover dataset (Jamieson et al., ICSE 2024), run as a check against the psychological-safety literature. Tests a question the authors did not ask: thin interpersonal communication tracks with losing veterans, not newcomers. Reports the finding and the tests that weaken it. | Python, pandas, scipy, Matplotlib |

## Certifications
**Data Scientist** — DataCamp (Jul 2026 – Jul 2028) · Credential ID: DS0022627785758
**Data Scientist Associate** — DataCamp (Oct 2025 – Oct 2027)
**GitHub Foundations** — DataCamp (Jun 2026 – Jun 2027)

## Contact
[LinkedIn](https://www.linkedin.com/in/mateus-fardin-pavan) · [mateusfardinpavan@gmail.com](mailto:mateusfardinpavan@gmail.com)
