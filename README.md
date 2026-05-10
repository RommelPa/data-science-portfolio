# Data Science Portfolio

## Overview

This repository is the central hub for my data science portfolio.

The portfolio demonstrates reproducible data analysis, machine learning, business reporting, dashboard development, model serving, containerized API delivery, and continuous integration.

The goal is not to show isolated notebooks. The goal is to show the full data-product workflow:

```text
business question → data audit → preprocessing → modeling → evaluation → interpretation → reporting → dashboard/API delivery → automation
```

---

## Professional Focus

I build reproducible data solutions that connect technical analysis with business decision-making.

My portfolio covers:

- exploratory data analysis,
- regression modeling,
- classification modeling,
- time series forecasting,
- natural language processing,
- executive dashboard development,
- machine learning APIs,
- Docker-based service packaging,
- GitHub Actions CI,
- Git/GitHub version control,
- reproducible local workflows.

---

## Portfolio Projects

| # | Project | Area | Main Deliverable | Repository |
|---:|---|---|---|---|
| 1 | Retail Sales EDA | Exploratory Data Analysis | Business-oriented retail sales analysis | [GitHub](https://github.com/RommelPa/retail-sales-eda) |
| 2 | House Prices Regression | Regression | Reproducible house price prediction workflow | [GitHub](https://github.com/RommelPa/house-prices-regression) |
| 3 | Customer Churn Classification | Classification | Churn prediction model with threshold analysis | [GitHub](https://github.com/RommelPa/customer-churn-classification) |
| 4 | Sales Forecasting Time Series | Forecasting | Daily sales forecasting with chronological validation | [GitHub](https://github.com/RommelPa/sales-forecasting-time-series) |
| 5 | Sentiment Analysis NLP | Natural Language Processing | IMDB sentiment classifier with TF-IDF and error analysis | [GitHub](https://github.com/RommelPa/sentiment-analysis-nlp) |
| 6 | Retail Executive Dashboard | Business Intelligence / Data App | Streamlit BI-style executive dashboard | [GitHub](https://github.com/RommelPa/retail-executive-dashboard) |
| 7 | Customer Churn Prediction API | ML Engineering / API | FastAPI churn prediction service with Docker and CI | [GitHub](https://github.com/RommelPa/customer-churn-prediction-api) |

---

## Featured Projects

### 1. Customer Churn Prediction API

**Repository:** [customer-churn-prediction-api](https://github.com/RommelPa/customer-churn-prediction-api)

This project converts a trained machine learning model into a usable API service.

It includes:

- reproducible model training,
- scikit-learn pipeline,
- FastAPI service,
- Pydantic request validation,
- `/health`, `/metadata`, and `/predict` endpoints,
- sample request and response,
- automated tests with pytest,
- Dockerfile and `.dockerignore`,
- Docker image validation,
- GitHub Actions CI workflow,
- CI-safe API contract tests with mocked model responses,
- MIT license,
- version tags `v1.0.0`, `v1.1.0`, and `v1.2.0`.

**Why it matters**

This project shows the transition from model development to model serving.

It demonstrates that a model is not useful only as a notebook artifact. It must be packaged, validated, documented, tested, containerized, and automatically checked through CI.

**Main technologies**

```text
Python, FastAPI, Pydantic, scikit-learn, pandas, joblib, pytest, Uvicorn, Docker, GitHub Actions
```

---

### 2. Retail Executive Dashboard

**Repository:** [retail-executive-dashboard](https://github.com/RommelPa/retail-executive-dashboard)

This project builds a BI-style executive dashboard with Streamlit.

It includes:

- raw retail data loading,
- dashboard-ready data preparation,
- KPI reconciliation checks,
- executive KPI cards,
- country filters,
- operational stock-code filtering,
- revenue trend,
- country mix,
- product ranking,
- customer concentration analysis,
- detailed tables,
- BI-style light theme,
- MIT license,
- version tag `v1.0.0`.

**Why it matters**

This project demonstrates the ability to transform transactional data into an executive-facing product.

It is not just exploratory analysis. It is a decision-support interface.

**Main technologies**

```text
Python, pandas, Streamlit, Plotly, Git, GitHub
```

---

### 3. Sales Forecasting Time Series

**Repository:** [sales-forecasting-time-series](https://github.com/RommelPa/sales-forecasting-time-series)

This project forecasts daily aggregate retail sales.

It includes:

- temporal data audit,
- daily aggregation,
- chronological train/validation/test splits,
- strong baselines,
- machine learning forecasting models,
- final test evaluation,
- bias analysis,
- trend and seasonality figures,
- executive summaries,
- MIT license,
- version tag `v1.0.0`.

**Why it matters**

Forecasting requires respecting time order. This project shows chronological validation instead of random splits, which is essential for time series work.

**Main technologies**

```text
Python, pandas, scikit-learn, statsmodels, matplotlib, time series validation
```

---

### 4. Sentiment Analysis NLP

**Repository:** [sentiment-analysis-nlp](https://github.com/RommelPa/sentiment-analysis-nlp)

This project builds a sentiment classifier for IMDB movie reviews.

It includes:

- text data audit,
- HTML cleanup,
- duplicate removal before splitting,
- stratified train/validation/test splits,
- TF-IDF features,
- model comparison,
- cross-validation,
- final test evaluation,
- confusion matrix,
- ROC and precision-recall curves,
- token interpretation,
- error analysis,
- MIT license,
- version tag `v1.0.0`.

**Why it matters**

This project demonstrates classic NLP modeling with proper preprocessing and validation. It also includes interpretation and error analysis, not just accuracy reporting.

**Main technologies**

```text
Python, pandas, scikit-learn, TF-IDF, Linear SVM, Logistic Regression, matplotlib
```

---

## Supporting Projects

### Customer Churn Classification

**Repository:** [customer-churn-classification](https://github.com/RommelPa/customer-churn-classification)

This project is the analytical foundation for the churn API.

It includes data audit, cleaning and preprocessing, classification model comparison, threshold analysis, final evaluation, interpretation, cross-validation, executive summaries, README documentation, MIT license, and version tag `v1.0.0`.

This project explains the modeling logic and business trade-offs behind churn prediction.

---

### House Prices Regression

**Repository:** [house-prices-regression](https://github.com/RommelPa/house-prices-regression)

This project builds a reproducible regression workflow for house price prediction.

It includes data loading and audit, preprocessing, model comparison, validation error analysis, cross-validation, final model selection based on stability, interpretation with Ridge coefficients, executive summaries, README documentation, MIT license, and version tag `v1.0.0`.

This project demonstrates regression fundamentals, model stability analysis, and interpretable reporting.

---

### Retail Sales EDA

**Repository:** [retail-sales-eda](https://github.com/RommelPa/retail-sales-eda)

This project performs exploratory retail sales analysis.

It includes raw data loading, data audit, cleaning, sales KPIs, product analysis, customer analysis, country analysis, cancellation analysis, business findings, executive reporting, and a reproducible local pipeline.

This project is the foundation for later retail business analytics and dashboard work.

---

## Skill Coverage Matrix

| Skill Area | Demonstrated In |
|---|---|
| Exploratory Data Analysis | Retail Sales EDA |
| Data Cleaning | All projects |
| Regression | House Prices Regression |
| Classification | Customer Churn Classification |
| Forecasting | Sales Forecasting Time Series |
| Natural Language Processing | Sentiment Analysis NLP |
| Dashboard Development | Retail Executive Dashboard |
| API Development | Customer Churn Prediction API |
| Model Serving | Customer Churn Prediction API |
| Docker | Customer Churn Prediction API |
| Continuous Integration | Customer Churn Prediction API |
| Automated Testing | Customer Churn Prediction API |
| Business Reporting | Retail Executive Dashboard, Churn, Forecasting, Regression |
| Model Interpretation | Regression, Churn, NLP |
| Error Analysis | Regression, NLP, Forecasting |
| Git/GitHub Workflow | All projects |
| Reproducibility | All projects |

---

## Technology Stack

### Languages

```text
Python
SQL concepts
Markdown
```

### Data and Modeling

```text
pandas
numpy
scikit-learn
statsmodels
joblib
```

### Visualization and Apps

```text
matplotlib
Plotly
Streamlit
```

### API and Engineering

```text
FastAPI
Pydantic
Uvicorn
pytest
httpx
Docker
GitHub Actions
Git
GitHub
```

---

## Recommended Reading Order

If you are reviewing this portfolio, use this order:

1. **Customer Churn Prediction API**  
   Best technical project. Shows model serving, validation, tests, Docker, and CI.

2. **Retail Executive Dashboard**  
   Best visual/business-facing project. Shows dashboard design and executive reporting.

3. **Sales Forecasting Time Series**  
   Best time-aware modeling project. Shows chronological validation and forecasting discipline.

4. **Sentiment Analysis NLP**  
   Best text modeling project. Shows NLP preprocessing, TF-IDF modeling, and token interpretation.

5. **Customer Churn Classification**  
   Best business classification project. Shows threshold analysis and retention trade-offs.

6. **House Prices Regression**  
   Good regression baseline project. Shows error analysis and model selection discipline.

7. **Retail Sales EDA**  
   Good foundational EDA project. Shows business-oriented exploratory analysis.

---

## Portfolio Narrative

This portfolio is designed to show progression.

It starts with exploratory analysis and supervised modeling. It then moves into forecasting and NLP. It continues with an executive dashboard and finishes with an API that serves a trained model through FastAPI, Docker, tests, and CI.

The key message is:

```text
I can analyze data, build models, explain results, create decision-support dashboards, and serve machine learning predictions through tested, containerized, CI-validated APIs.
```

---

## Current Status

| Project | Status |
|---|---|
| Retail Sales EDA | Complete |
| House Prices Regression | Complete, tagged `v1.0.0` |
| Customer Churn Classification | Complete, tagged `v1.0.0` |
| Sales Forecasting Time Series | Complete, tagged `v1.0.0` |
| Sentiment Analysis NLP | Complete, tagged `v1.0.0` |
| Retail Executive Dashboard | Complete, tagged `v1.0.0` |
| Customer Churn Prediction API | Complete, tagged `v1.2.0` |

---

## Next Improvements

The portfolio is already broad enough. The next improvements should focus on polish, deployment, and automation rather than adding more notebooks.

Recommended next steps:

1. Deploy the Retail Executive Dashboard.
2. Deploy the Customer Churn Prediction API.
3. Add Docker image publishing workflow for the API.
4. Add screenshots or demo GIFs to this hub.
5. Add direct demo links when deployments are available.
6. Add a short professional profile section to LinkedIn using this portfolio narrative.

---

## Spanish Summary

Este repositorio centraliza mi portafolio de ciencia de datos.

El portafolio demuestra proyectos reproducibles de análisis exploratorio, regresión, clasificación, forecasting, NLP, dashboard ejecutivo, API de machine learning, Docker y CI con GitHub Actions.

La narrativa principal es:

```text
Construyo soluciones de datos reproducibles: desde análisis y modelado hasta dashboards ejecutivos y APIs de inferencia.
```

Los proyectos muestran el flujo completo de trabajo:

```text
pregunta de negocio → auditoría de datos → limpieza → modelado → evaluación → interpretación → documentación → entrega como dashboard o API → automatización
```

El objetivo no es acumular notebooks. El objetivo es demostrar capacidad para entregar soluciones de datos completas, verificables y automatizadas.