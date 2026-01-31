# Modeling Overview

This section describes the modeling strategy for early anomaly detection using multi-signal surveillance data.

## 1. Modeling Goals
- Detect unusual respiratory patterns before clinical emergence  
- Generate anomaly scores for each signal and combined signals  
- Provide interpretable early-warning indicators  

## 2. Model Categories Considered

### A. Time-Series Models
- ARIMA / SARIMA  
- STL decomposition + anomaly thresholds  
- Prophet or NeuralProphet  

### B. Machine-Learning Models
- Isolation Forest  
- One-Class SVM  
- Random forest anomaly models  
- Gradient boosting anomaly models  

### C. Deep-Learning Models
- LSTM Autoencoders  
- Temporal Convolutional Networks (TCN)  
- Variational Autoencoders (VAE) for anomaly scoring  

## 3. Model Evaluation  
- Precision of anomaly detection  
- Sensitivity to early-signal changes  
- False-positive rate  
- Lead-time gained before ED surge or hospitalisation rise  

## 4. Output Location
All model outputs and anomaly scores will be stored here:

/analytics/model_outputs/
/analytics/anomaly_scores/
