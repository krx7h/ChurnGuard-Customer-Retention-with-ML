# ChurnGuard: Customer Retention with ML

Predicting customer churn using machine learning to help businesses retain their customers and take proactive actions. This project uses structured CRM data and implements a complete ML pipeline from preprocessing to evaluation using **XGBoost**.

---

## 📊 Problem Statement

Customer churn is a major concern for subscription-based businesses. Identifying customers who are likely to leave allows companies to intervene and retain them. This project builds a predictive model to classify whether a customer will churn or not based on their usage patterns and demographics.

---

## 🔧 Features

--> Cleaned and preprocessed customer churn dataset  
--> Handled missing values and converted categorical features  
--> Performed feature selection using `SelectKBest`  
--> Used **SMOTE** to handle class imbalance  
--> Trained with **XGBoostClassifier** and optimized threshold  
--> Evaluated using **confusion matrix**, **recall**, and **F1-score**

---

## 📈 Model Performance

- **Recall for Churn = Yes customers:** 81%  
- **True Positives (Correctly predicted churn):** 303 out of 373  
- **Accuracy:** ~77%

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- imbalanced-learn (SMOTE)  
- Matplotlib/Seaborn (for optional visualizations)

---

