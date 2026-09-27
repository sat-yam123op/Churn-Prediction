# Customer Churn Prediction – End-to-End MLOps Project

An end-to-end Machine Learning project that predicts whether a customer is likely to churn based on customer demographic, service, contract, and billing information.

The project includes a trained Machine Learning model, a FastAPI prediction API, and a web-based frontend deployed on Render.

## 🚀 Live Demo

### Frontend
https://churn-prediction-frontend-ja99.onrender.com/

### Prediction API
https://churn-prediction-euo6.onrender.com/

### API Documentation
https://churn-prediction-euo6.onrender.com/docs

---

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to stop using their services.

This project takes customer information such as:

- Gender
- Senior Citizen status
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming Services
- Contract Type
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges

and predicts:

- Whether the customer is likely to churn
- The probability of churn

Example output:

```json
{
  "prediction": "No Churn",
  "churn_probability": 0.228
}
