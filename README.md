# CBSOT-SIP
# 📊 Telco Customer Churn Prediction

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project aims to predict whether a customer is likely to leave the service using Machine Learning techniques. By identifying customers at risk of churning, businesses can take proactive measures to improve customer retention.

---

## 🎯 Objectives

* Analyze customer behavior and service usage patterns.
* Perform Exploratory Data Analysis (EDA) to identify churn trends.
* Clean and preprocess customer data.
* Build Machine Learning models for churn prediction.
* Compare model performance and identify key churn factors.

---

## 📂 Dataset

The dataset contains customer information such as:

* Customer Demographics
* Tenure Months
* Monthly Charges
* Total Charges
* Contract Type
* Internet Service
* Payment Method
* Tech Support
* Online Security
* Streaming Services
* Churn Label (Target Variable)

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Distribution of customer tenure
* Distribution of monthly charges
* Churn vs Tenure Analysis
* Churn vs Monthly Charges
* Contract Type vs Churn
* Internet Service vs Churn
* Payment Method vs Churn
* Tech Support vs Churn
* Online Security vs Churn
* Streaming Services vs Churn
* Correlation Analysis of numerical features

### Key Insights

* Customers with month-to-month contracts are more likely to churn.
* Higher monthly charges show a stronger tendency toward churn.
* Customers without Tech Support and Online Security services churn more frequently.
* Longer tenure customers are less likely to leave.

---

## 🧹 Data Preprocessing

### Data Cleaning

* Converted `Total Charges` to numeric datatype.
* Handled missing values.
* Removed unnecessary columns.

### Feature Engineering

* Label Encoding applied to categorical variables.
* Feature selection performed before model training.

### Train-Test Split

* 80% Training Data
* 20% Testing Data

---

## 🤖 Machine Learning Models

### 1. Logistic Regression

* StandardScaler used for feature scaling.
* Model trained on scaled data.

### 2. Random Forest Classifier

* 200 Decision Trees
* Random State = 42

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

  * Precision
  * Recall
  * F1-Score

---

## 🏆 Results

| Model               | Evaluation                                       |
| ------------------- | ------------------------------------------------ |
| Logistic Regression | Baseline Model                                   |
| Random Forest       | Better Performance & Feature Importance Analysis |

Random Forest performed better in identifying churn patterns and provided feature importance rankings.

---

## 🔑 Important Features Influencing Churn

Top churn-driving factors identified using Random Forest:

* Tenure Months
* Monthly Charges
* Total Charges
* Contract Type
* Internet Service
* Tech Support
* Online Security

---

## 📁 Project Structure

```text
Telco-Customer-Churn-Prediction/
│
├── cbsot_project.ipynb
├── Telco_customer_churn.xlsx
├── README.md
│
├── EDA
├── Data Cleaning
├── Feature Engineering
├── Model Training
├── Model Evaluation
└── Feature Importance Analysis
```

---

## 📊 Future Improvements

* Hyperparameter Tuning
* Cross Validation
* XGBoost Implementation
* SMOTE for Class Imbalance Handling
* Model Deployment using Flask/Streamlit
* Real-Time Churn Prediction Dashboard

---


