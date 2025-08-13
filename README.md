# Credit Card Fraud Detection

Machine learning project for detecting fraudulent transactions using multiple classification models 

---

## 📌 Problem Statement

Credit card fraud is a serious issue with highly imbalanced datasets. The goal of this project is to:

- Train & evaluate multiple ML classifiers
- Handle data imbalance using SMOTE
- Tune models for optimal performance

---

## 📂 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions | 492 fraud cases
- Features: `V1` to `V28` (anonymized), `Time`, `Amount`
- Target: `Class` (1 = Fraud, 0 = Not Fraud)

---

## 🧠 Models Used

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- Gradient Boosting  
- XGBoost (tuned using RandomizedSearchCV)

All models were trained on SMOTE-balanced data and evaluated on an untouched imbalanced test set.

---

## 📊 Evaluation Metrics

- **Precision**, **Recall**, **F1-Score**
- **Confusion Matrix**
- **ROC-AUC Curve**
