# Deployment & Monitoring Plan

## 1. Deployment Architecture
- Containerised model inference (Docker)
- API endpoint for anomaly scoring (FastAPI or Flask)
- Batch pipeline for daily/weekly signal ingestion
- Scheduler (Airflow / Prefect / Cron)

## 2. Monitoring Metrics
- Model drift (KL divergence, PSI)
- Data quality drift (missingness, volume anomalies)
- Alert volume calibration
- Lead-time stability
- False positive rate (FPR) over rolling 4-week windows

## 3. Alerting Mechanism
- Threshold-based anomaly alerts
- Change-point detection monitoring
- SMS/Email webhook triggers (Twilio, SendGrid)

## 4. Logging & Audit
- Store all inference outputs in `/logs/model_inference/`
- Store alert triggers in `/logs/alerts/`

## 5. Retraining Strategy
- Rolling retrain every 30/60 days
- Trigger retraining if drift crosses threshold
- Human-in-loop review before deployment

## Output Location
Deployment scripts will be placed in: `/src/deployment/`
