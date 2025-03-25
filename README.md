# 💼 Financial Fraud Detection – Exploratory Data Analysis (EDA)

A comprehensive case study analyzing the **Financial Datasets for Fraud Detection** from Kaggle.  
This project explores transaction patterns, uncovers fraud behaviors, and builds a foundation for future machine learning-based fraud detection models.

---

## 📌 Project Overview

- **Dataset:**  Financial Transactions Dataset 
- **Total Transactions:** 6.3M+  
- **Fraud Cases:** 8,213 (~0.13%)  
- **Objective:** Explore transaction patterns, detect anomalies, and derive actionable insights for fraud detection systems.

---

## 🧠 Key Insights

- Fraud occurs **only in `TRANSFER` and `CASH_OUT`** transactions.
- Fraud is **4x more likely** in `TRANSFER` than in `CASH_OUT`.
- **98% of fraudulent senders** are drained to ₹0 after the transaction.
- Fraudsters frequently use large round amounts like **₹10 million** or **₹0 balances** before initiating fraud.
- Real (non-fraud) transactions typically **leave a balance behind**.
- **Balance differences** and starting balances show strong correlation with fraudulent behavior.

---

## 📁 Contents

| File / Folder            | Description                                  |
|--------------------------|----------------------------------------------|
| `Financial_Fraud_Analysis.ipynb` | Full EDA notebook with visualizations and commentary |
| `README.md`              | This file                                    |

---

## 🔧 Tech Stack

- **Language:** Python 3  
- **Libraries:** Pandas, Matplotlib, Seaborn, Numpy, Scikit-learn  

---

## 📈 Future Work

- Feature engineering for predictive models  
- Handling class imbalance with SMOTE/undersampling  
- Model training (Logistic Regression, Random Forest, XGBoost)  
- Real-time fraud detection pipeline

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---



