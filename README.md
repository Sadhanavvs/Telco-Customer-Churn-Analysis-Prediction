# Telco-Customer-Churn-Analysis-Prediction
# 📊 Telco Customer Churn Analysis & Prediction

## 🚀 Project Overview

This project focuses on analyzing customer churn in a telecom company and building machine learning models to predict which customers are likely to leave.

Customer churn is a critical business problem. By identifying at-risk customers, companies can take proactive actions to improve retention.

---

## 🎯 Objectives

* Understand customer behavior through data analysis
* Identify key factors affecting churn
* Build machine learning models to predict churn
* Improve model performance using advanced techniques

---

## 📁 Dataset

* Dataset: Telco Customer Churn Dataset
* Format: CSV
* Features include:

  * Customer demographics (gender, senior citizen, etc.)
  * Account information (tenure, contract type)
  * Services used (internet, phone, streaming)
  * Billing details (monthly charges, total charges)
  * Target variable: `Churn` (Yes/No)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading

* Loaded dataset using pandas
* Verified structure using `.head()`, `.info()`

### 2. Data Cleaning

* Handled missing values
* Converted `TotalCharges` to numeric
* Removed null values

### 3. Exploratory Data Analysis (EDA)

* Churn distribution visualization
* Churn by Internet Service
* Identified imbalance in dataset

### 4. Data Preprocessing

* Converted categorical variables using one-hot encoding
* Converted target variable (Churn → 0/1)
* Split dataset into training and testing sets

### 5. Model Building

* Logistic Regression
* Random Forest Classifier

### 6. Model Evaluation

* Accuracy Score
* Classification Report (Precision, Recall, F1-score)

---

## 📈 Results

* Logistic Regression Accuracy: ~72%
* Random Forest Accuracy: Improved performance
* Key Insight: Model needs to focus on predicting churn customers (class 1)

---

## 🔥 Key Insights

* Customers with month-to-month contracts are more likely to churn
* Higher monthly charges increase churn probability
* Lack of long-term commitment is a major factor

---

## 📊 Sample Visualization

* Customer Churn Distribution
* Feature Importance (Random Forest)

---

## 🧠 Future Improvements

* Use advanced models (XGBoost, Gradient Boosting)
* Hyperparameter tuning
* Handle class imbalance using SMOTE
* Deploy model using Flask or Streamlit

---

## 📌 How to Run

```bash
pip install pandas numpy matplotlib scikit-learn
python churn_analysis.py
```

---

## ⭐ Author

Sadhana VVS

---

## 📎 License

This project is for educational purposes.

