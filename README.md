# Fraud Detection ML Model

A machine learning model to detect fraudulent credit card transactions using Logistic Regression, trained on a dataset of 284,807 transactions.

##  Model Performance

- **Accuracy:** 99.91%
- **ROC-AUC:** 0.976 (Excellent)
- **Precision (Fraud):** 0.85 (85% of flagged transactions are actually fraud)
- **Recall (Fraud):** 0.56 (Catches 56% of fraudulent transactions)

`2. **Fraud Probability:** Confidence it's fraudulent (0-1)
3. **Legitimate Probability:** Confidence it's legitimate (0-1)

### Decision Threshold
- Current threshold: 0.5 (default)
- If fraud_probability > 0.5 → Fraud
- Lower threshold = catch more fraud but more false alarms
- Higher threshold = fewer false alarms but miss more fraud

