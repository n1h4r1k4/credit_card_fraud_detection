# 💳 Credit Card Fraud Detection using Machine Learning

## 🧠 Project Overview
This project focuses on detecting fraudulent credit card transactions using **Machine Learning**.  
It leverages **Logistic Regression**, a supervised classification algorithm, to identify whether a transaction is **legitimate (0)** or **fraudulent (1)** based on various anonymized features.

---

## ✨ Features
✅ **Data Preprocessing:** Handles scaling and splitting of data.  
✅ **Model Training:** Uses Logistic Regression for binary classification.  
✅ **Evaluation Metrics:** Accuracy, Confusion Matrix, and Classification Report.  
✅ **Imbalanced Data Handling:** Stratified splitting maintains class ratio.  
✅ **Sample Testing:** Predicts whether a random transaction is Fraud or Not Fraud.  
✅ **Easily Extendable:** Can be enhanced with advanced algorithms (Random Forest, XGBoost, etc.)

---

## 📦 Installation

### 🧩 Dependencies
Install the following libraries before running the project:

```bash
pip install pandas numpy scikit-learn

⚙️ Data Collection
📁 Dataset

Download the dataset from Kaggle:
👉 Credit Card Fraud Detection Dataset

About the Dataset:

Source: Machine Learning Group – ULB (Université Libre de Bruxelles)

Total Transactions: 284,807

Fraudulent Transactions: 492

Time Period: September 2013

Target Column: Class

0 → Normal Transaction

1 → Fraudulent Transaction

Place the dataset (creditcard.csv) in the project directory before running the script.
