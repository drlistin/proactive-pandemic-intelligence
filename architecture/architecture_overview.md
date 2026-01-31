# Architecture Overview

This folder documents the ROAD lifecycle for the **Proactive Pandemic Intelligence** project.

- **R – Requirements**  
  Defined in `requirements.md`: problem framing, stakeholders, and success criteria.

- **O – Operationalise Data**  
  - `data/datasources_overview.md` – candidate data streams and access notes  
  - `synthetic_data_plan.md` – how we will simulate realistic, privacy-preserving data

- **A – Analytics**  
  - `analytics_plan.md` – overall modelling strategy  
  - `analytics/analytics_overview.md` – signal preprocessing & anomaly-detection stack  
  - `analytics/feature_engineering.md` – clinical features and cross-signal features

- **D – Deployment**  
  - `deployment_plan.md` – deployment, monitoring, and retraining strategy  
  - `validation_overview.md` – how we will test, validate, and monitor model performance

This file is just a map so reviewers can quickly understand how the project is structured.
