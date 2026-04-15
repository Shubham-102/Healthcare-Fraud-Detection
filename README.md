# 🏥 Healthcare Provider Fraud Detection

## 📌 Project Overview

This project focuses on detecting fraudulent healthcare providers using machine learning techniques on Medicare claims data.

Healthcare fraud leads to billions of dollars in losses annually. This project aims to identify suspicious providers based on claim patterns, billing behavior, and patient data.

---

## 📊 Dataset

* Source: Kaggle - Healthcare Provider Fraud Detection Analysis
* Includes:

  * Beneficiary data (patient demographics)
  * Inpatient claims
  * Outpatient claims
  * Provider fraud labels

---

## ⚙️ Project Workflow

1. Data Loading and Merging
2. Data Cleaning and Handling Missing Values
3. Feature Engineering
4. Provider-Level Aggregation
5. Model Building (Random Forest, XGBoost)
6. Model Evaluation

---

## 🔍 Key Features Engineered

* Claim Duration
* Average Claim Amount
* Total Claim Amount
* Claim Count per Provider
* Average Patient Age

---

## 🤖 Models Used

* Random Forest Classifier
* XGBoost Classifier

---

## 📈 Results

* Best Model: Random Forest
* Fraud Detection Recall: **68%**
* Improved precision using class balancing

---

## 🚨 Key Insights

* Fraudulent providers tend to:

  * Submit higher claim amounts
  * Have higher claim frequency
  * Show abnormal claim durations

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib

---

## 📁 Project Structure

```
Healthcare-Fraud-Detection/
│
├── data/
├── notebooks/
│   └── fraud_detection.ipynb
├── README.md
├── requirements.txt
```

---

## 🚀 Future Improvements

* Add SHAP explainability
* Deploy using Streamlit
* Improve recall using advanced models

---

