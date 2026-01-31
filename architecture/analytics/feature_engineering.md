# Feature Engineering Plan

## 1. Purpose
Define engineered features that enhance the predictive power of multi-signal early-warning models.  
Features are derived from time-series changes, correlations, and signal-specific patterns.

## 2. Feature Categories

### A. Temporal Features
- Rolling averages (7d, 14d, 28d)
- Moving standard deviation
- Week-on-week change
- Month-on-month change

### B. Statistical Features
- Z-scores
- Percentile shifts
- Anomaly scores (IQR, MAD)

### C. Change-Point Features
- CUSUM statistics
- BOCPD markers (Bayesian Online Change Detection)
- Slope change indicators

### D. Cross-Signal Features
- Correlation between search trends and ED visits
- Lagged correlations between wastewater and hospital data
- Predictive cross-covariance signals

### E. Domain-Specific Features
- Symptom-based clusters
- Prescription pattern spikes
- Wearable signal volatility (e.g., resting HR)

## 3. Output Location
Engineered feature tables will be stored in: /data/processed/features/

