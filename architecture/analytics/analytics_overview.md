# Analytics Overview

This folder contains the analytical logic for early detection of novel respiratory threats.  
The analytics pipeline will process multi-signal data sources (search trends, ED visits, prescriptions, wastewater, genomics, and wearables) to generate anomaly signals.

## Key Components

### 1. Signal Preprocessing
- Noise filtering  
- Normalisation  
- Missing-value handling  
- Seasonal decomposition  

### 2. Feature Engineering
- Rolling averages  
- Week-on-week change  
- Z-scores  
- Change-point features  
- Cross-signal correlation features  

### 3. Anomaly Detection
- Prophet trend deviation  
- STL residual spikes  
- Isolation Forest  
- Seasonal ESD (Extreme Studentized Deviate)  
- Bayesian online change-point detection  

### 4. Output
- Daily risk score  
- Classified alerts: *Low, Moderate, High*  
- Explanation metadata  
