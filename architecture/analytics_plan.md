Analytics Plan (High-Level)

This document outlines the planned analytics and modeling approaches for Proactive Pandemic Intelligence.

1. Anomaly Detection (Core)

Detect unusual spikes in respiratory-related signals.

Compare real-time values against historical baselines.

Use simple first models:

Moving averages

Z-score anomaly detection

Seasonal decomposition

2. Multi-Stream Fusion

Each data stream contributes differently to early warning.
We will explore weighted fusion of:

Search trends

ED visits

Prescriptions

Wearable signals

Wastewater/genomics

Outputs will be combined into a Composite Early Warning Index.

3. Time-Series Forecasting (Optional Phase 2)

Predict short-term increases in respiratory activity (7–21 days).

Candidate models:

Prophet

LSTM (later, optional)

Gradient boosting with lagged features

4. Model Evaluation Strategy

Backtesting using historical respiratory outbreaks

Compare signals 2–8 weeks before clinical detection

Metrics:

Sensitivity to early signals

False-alarm rate

Lead time gained

More detailed notebooks will be added later in the /notebooks folder.
