Proactive Pandemic Intelligence
AI-Driven Architecture for Pre-Emergence Detection of Novel Respiratory Threats

Early anomaly detection system using multi-signal surveillance (search trends, ED visits, prescription patterns, wearable signals, wastewater, and genomics) to identify respiratory threats before they emerge clinically.

1. Problem Statement

Pandemics often start silently;before hospitals see abnormal admissions.
Traditional public-health reporting has 2–8 week delays, causing late interventions.
This project explores AI-based early-warning signals combining multiple heterogeneous data streams to detect anomalies before classical surveillance detects anything.

2. System Architecture (High-Level)

(Diagram will be added later in /architecture/system_architecture.png)

Core Modules:

Data ingestion pipelines

Signal transformation & harmonization

Multi-modal anomaly detection

Early-warning risk scoring

Dashboard for decision intelligence

3. Data Sources (Synthetic / Public)

Data stored under /architecture/data/:

Google Trends (cough, fever, SOB queries)

ED visit volumes (open NHS data)

Prescription patterns (antibiotics, antivirals-synthetic)

Wearable-derived signals (HRV, resting HR-synthetic)

Wastewater viral load

Genomic mutation emergence signals

4. Analytics Pipeline

Notebooks in /notebooks/ will cover:

Exploratory signal analysis

Multi-signal time-series profiling

Lag correlations

Composite anomaly-score generation

Early trend inflection detection

5. Model Approach

Code under /src/ will contain:

Isolation Forest for anomaly detection

LSTM Autoencoders for sequence reconstruction

Bayesian Change-Point Detection

Signal Fusion Model combining multi-modal inputs

Early-warning scoring algorithm

6. Deployment Strategy

Planned deployment:

Minimal FastAPI service

Containerized via Docker

Optional cloud execution (AWS Lambda / Azure Functions)

Dashboard UI for real-time risk index

7. Roadmap

 Add synthetic datasets

 Create architecture diagrams

 Implement multi-signal anomaly models

 Build risk-score fusion algorithm

 Add evaluation framework

 Deploy minimal API

 Build dashboard

 Add white-paper style documentation

8. Why This Project Matters

This project demonstrates:

Ability to architect end-to-end clinical AI systems

Understanding of public-health surveillance

Strong technical depth across data, analytics, MLOps

Product-thinking aligned with Dr Ian’s JHU framework (ROAD)

Recruiter-visible portfolio-ready AI leadership

9. Contact

 Dr Doju Cherian (DrListin)
Internal Medicine Trainee
Sheffield Teaching Hospital.
