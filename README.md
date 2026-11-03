# Kelvin W. Maina

**Data Scientist · ML Engineer**

> Synthesizing empirical machine learning, edge computer vision, and high-throughput data platforms to empower real-world agricultural and fintech resilience.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connected-0077b5?style=flat&logo=linkedin)](https://linkedin.com/in/kelvin-maina)
[![Email](https://img.shields.io/badge/Email-Verified-fabc45?style=flat&logo=gmail)](mailto:kelvin.maina.ds@gmail.com)

---

## About Me

Applied AI practitioner focused on scalable deep learning solutions, predictive risk analytics, and production-grade MLOps deployment. Passionate about bringing algorithmic intelligence from notebook experiments into high-reliability cloud pipelines.

```python
developer = {
    "name": "Kelvin W. Maina",
    "role": "Staff Data Scientist / ML Engineer",
    "primary_specialty": ["Edge CV", "Tabular Ensembles", "MLOps"],
    "deployment_targets": ["FastAPI", "Docker", "Triton", "AWS"],
    "core_metrics": {
        "f1_target": 0.942,
        "p99_latency_ms": 42,
        "production_deployments": 28
    }
}
```

## Selected Projects

### AgriVision: Leaf Pathology Computer Vision

![Status: Production](https://img.shields.io/badge/status-production-3fb950?style=flat)
![mAP@0.5](https://img.shields.io/badge/mAP%400.5-96.8%25-67df70?style=flat)

An end-to-end computer vision system that detects and classifies foliar diseases in maize crops across four categories, achieving 93.6% test accuracy and a 0.94 weighted F1-score using transfer learning on MobileNetV3.

To handle real-world dataset imbalance and runtime constraints, the project uses weighted sampling, data augmentation, and an unfreezing fine-tuning strategy, with strict image integrity checks and structured logging. The model is productionized as a containerized FastAPI backend, an interactive Streamlit diagnostic dashboard, and automated CI/CD pipelines via GitHub Actions.

**Stack:** PyTorch, TorchScript, FastAPI, TensorRT

### Fintech Churn Radar and Waterfall Interpretability

![AUC-ROC](https://img.shields.io/badge/AUC--ROC-0.931-67df70?style=flat)

A customer retention analytics system that predicts churn probability for retail banking customers. A reproducible scikit-learn data pipeline ingests demographic, account balance, and product interaction signals to score attrition risk.

The model is packaged behind a Flask web application with a responsive UI that gives account managers immediate risk categories and probability scores to trigger targeted retention campaigns. SHAP explanations make each prediction interpretable.

**Stack:** LightGBM, SHAP TreeExplainer, Optuna

### GeoHarvest: Yield Prediction Engine

![RMSE](https://img.shields.io/badge/RMSE-4.1%20bushels-67df70?style=flat)

Integrates Sentinel-2 spectral indices, weather forecast grids, and ground telemetry into spatiotemporal models that forecast crop yields at micro-climate scale.

**Stack:** Google Earth Engine API, XGBoost Regressor, GeoPandas

### AgriCredit: Alternative Risk Scoring

![Gini](https://img.shields.io/badge/Gini-0.78-3fb950?style=flat)

Underwriting models that combine mobile transactions, farm acreage telemetry, and seasonal liquidity profiles to expand credit access to smallholder farmers safely.

**Stack:** Scikit-Learn, Streamlit, PostgreSQL

## Architecture

```text
[ INGESTION ]  -->  [ MODELING CORE ]         -->  [ SERVING LAYER ]
-----------------------------------------------------------------
Sentinel Sat   -\
IoT Soil Nodes --> [ GeoSpatial Regressors ]  -> [ Farm Dashboard ]
M-Pesa Ledger  --> [ Credit Risk Ensembles ]  -> [ Instant Loan API ]
Camera Feed    --> [ Edge YOLOv8 Detectors ]  -> [ Mobile Offline ]
-----------------------------------------------------------------
           \                  |                  /
            ===> [ MLflow Tracking Registry ] <===
            ===> [ Automated Drift Triggers ] <===
```

## Tech Stack

**Machine Learning and Data Science:** Python 3.11, PyTorch, TensorFlow, Scikit-Learn, XGBoost, LightGBM, Pandas, Polars, OpenCV, SHAP

**Deployment, MLOps and Serving:** Docker, FastAPI, Flask, MLflow, AWS SageMaker, GitHub Actions CI/CD, Streamlit

**Databases and Data Platforms:** PostgreSQL, pgvector, Redis, DuckDB, SQLAlchemy, Apache Airflow

**Analytics, BI and Full-Stack:** Tableau, Power BI, TypeScript, Next.js, Tailwind CSS

## Contact

- **Email:** kelvin.maina.ds@gmail.com
- **LinkedIn:** [linkedin.com/in/kelvin-maina](https://linkedin.com/in/kelvin-maina)
- **GitHub:** [github.com/kelvinmaina](https://github.com/kelvinmaina)

---

Available for technical advisory and ML research engagements.

> Code is temporary. Architected intelligence endures.
