


# 📊 Telco Customer Churn Dataset (IBM Sample Data)

Dataset available here: [IBM Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## 🔎 Introduction
This dataset contains customer data from a fictional telecommunications company.  
It captures **demographics, account information, subscribed services, and billing details** for ~7,000 customers, along with an indicator of whether they **churned** (canceled their subscription) or not.  

It is commonly used for **churn prediction models** and customer retention analysis.

---

## 📦 Dataset Structure
- **Rows**: 7,043 customers  
- **Features**: 21 explanatory variables  
- **Target**: `Churn` (Yes / No)

---

## 📌 Variables Overview

### 1. Customer Demographics
- `customerID` : Unique customer identifier  
- `gender` : Male / Female  
- `SeniorCitizen` : 0 (No) / 1 (Yes)  
- `Partner` : Yes / No  
- `Dependents` : Yes / No  

### 2. Account Information
- `tenure` : Months with the company  
- `Contract` : Month-to-month / One year / Two year  
- `PaperlessBilling` : Yes / No  
- `PaymentMethod` : Electronic check, Mailed check, Bank transfer, Credit card  

### 3. Services Signed Up
- `PhoneService` : Yes / No  
- `MultipleLines` : Yes / No / No phone service  
- `InternetService` : DSL, Fiber optic, No  
- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`  
- `StreamingTV`, `StreamingMovies`  

*(All Yes / No / No internet service)*  

### 4. Billing
- `MonthlyCharges` : Monthly amount charged  
- `TotalCharges` : Total amount charged  

### 5. Target Variable
- `Churn` : Yes (customer left) / No (customer stayed)  

---

## 🎯 Use Cases
- Build **classification models** to predict churn  
- Identify **customer segments at risk**  
- Analyze **key churn drivers** (e.g., contract type, billing, services)  
- Create **visual dashboards** for customer retention strategies  
