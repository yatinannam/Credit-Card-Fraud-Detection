#  Credit Card Fraud Detection using Machine Learning

A beginner-friendly machine learning project to detect fraudulent credit card transactions using a Logistic Regression model.

---

##  Overview

This project uses a real-world credit card dataset to build a model that identifies scam transactions. The dataset is highly imbalanced, so we balance it, train a model, and evaluate its performance.

---

## 🛠 Tech Stack

- Python 
- Pandas 
- Scikit-learn 
- Google Colab 

---

##  How It Works

1. **Load Data:** Read the credit card transaction data.
2. **Preprocess:**
   - Handle class imbalance using undersampling
   - Separate features and target labels
3. **Train Model:** Logistic Regression
4. **Evaluate:** Accuracy, precision, recall, F1-score, and confusion matrix

---

##  Results

- **Model Used:** Logistic Regression
- **Accuracy:** ~92%
- **Precision (Fraud):** 94%
- **Recall (Fraud):** 92%

```text
Confusion Matrix:
[80  7]
[ 9 101]
```

---

## Dataset

- Source: Kaggle
- Dataset Name: Credit Card Fraud Detection
- Records: 284,807 transactions
- Features: 30 total (anonymized for privacy)
- Target Column: Class
  - 0 = Legitimate
  - 1 = Fraudulent

---

## Features

- Uses real financial transaction data
- Preprocessing with class balancing (undersampling)
- Beginner-friendly and well-commented code
- Evaluation using standard ML metrics
- Can be extended with other models or dashboards

---

## Future Improvements
- Try different ML algorithms
- Use SMOTE (oversampling) instead of just undersampling
- Deploy the model using Flask, Streamlit, or FastAPI
- Add visualizations for fraud distribution and feature insights
