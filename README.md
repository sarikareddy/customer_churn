# 📉 Customer Churn Prediction using Machine Learning

## 📌 Project Overview
Customer churn prediction helps businesses identify customers who are likely to leave the service.  
This project uses **machine learning classification algorithms** to predict churn based on historical customer data.

The implementation is done using **Google Colab** and the **Telco Customer Churn dataset**.

---

## 📂 Dataset
- Dataset name: **Telco Customer Churn**
- File used: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Target column: `Churn`
  - `0` → Customer stays
  - `1` → Customer churns

---

## 🛠 Tools & Technologies
- Python
- Google Colab
- Pandas
- Scikit-learn
- Logistic Regression
- Random Forest Classifier

---

## ⚙️ Project Workflow

### 1. Data Loading
- Dataset uploaded to Google Colab
- Loaded from `/mnt/data/`

### 2. Data Preprocessing
- Converted `Churn` column to numeric values
- Removed customer ID
- Converted categorical variables using Label Encoding
- Handled missing values in `TotalCharges`

### 3. Feature & Target Split
- Features (`X`) → customer attributes
- Target (`y`) → churn status

### 4. Train-Test Split
- 80% data for training
- 20% data for testing

---

## 🤖 Models Used

### Logistic Regression
- Simple and interpretable classification model
- Used as a baseline model

### Random Forest Classifier
- Ensemble learning model
- Handles non-linear relationships effectively
- Provides better churn prediction accuracy

---

## 🧪 Manual Testing

### Testing with a single customer
```python
sample = X_test.iloc[0:1]
prediction = lr.predict(sample)
```

---

## Author
Srigowri Cheboyina
