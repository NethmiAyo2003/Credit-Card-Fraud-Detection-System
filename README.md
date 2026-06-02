# Enterprise Credit Card Fraud Detection System

This repository contains a machine learning pipeline built inside a **Kali Linux environment** to detect fraudulent credit card transactions. It specifically addresses the real-world banking challenge of extreme data imbalance.

## Cyber Security & Compliance Alignment

* **PCI-DSS (Requirement 10 & 11) Compliance:** This system demonstrates how automated behavior profiling can be used to monitor cardholder data and flag anomalies, aligning with international payment card security standards.
* **CBSL Technology Risk Resiliency Framework:** Implements automated anomaly detection models as recommended by the Central Bank of Sri Lanka for fraud monitoring in commercial banks.

## Technical Implementation
* **OS Environment:** Developed and tested within Kali Linux.
* **Algorithm:** Random Forest Classifier (100 Decision Trees).
* **Data Balancing:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique) to handle highly imbalanced financial data.
* **Serialization:** The trained model is fully exported and ready for production deployment via `credit_card_fraud_model.pkl`.

## Key Performance Metrics
* **Fraud Detection Recall:** 78% (Successfully catching the majority of fraud instances).
* **Precision:** 85% (Low false-positive alarms to ensure minimal customer friction).
