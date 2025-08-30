# 📊 Telco Customer Churn Analysis

## Overview
This notebook performs an end-to-end analysis of customer churn prediction using various machine learning models. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and model training with cross-validation.

## Dataset
Dataset available here: [IBM Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)


## 🛠️ Dependencies
```python
catboost==1.2.2
lightgbm==4.1.0
xgboost==2.0.1
imbalanced-learn==0.11.0
pandas==2.1.1
numpy==1.24.3
scikit-learn==1.3.0
seaborn==0.12.2
matplotlib==3.8.0
```

## 📋 Project Structure
1. **Data Loading & Cleaning**
   - Load Telco customer dataset
   - Handle missing values in TotalCharges
   - Convert data types and standardize categories

2. **Exploratory Data Analysis**
   - Target variable distribution analysis
   - Categorical features analysis with chi-square tests
   - Numerical features correlation analysis
   - Multicollinearity check using VIF

3. **Feature Engineering**
   - One-hot encoding for categorical variables
   - Feature selection based on statistical tests
   - Handling class imbalance using SMOTE and ADASYN

4. **Model Training & Evaluation**
   - Models implemented:
     - Random Forest
     - XGBoost
     - CatBoost
     - LightGBM
   - 5-fold cross-validation
   - Performance metrics:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
     - ROC-AUC

## 📈 Key Findings
- Target variable is imbalanced (~27% churn rate)
- Contract type strongly correlates with churn
- Tenure and monthly charges are significant predictors
- Tree-based models show robust performance (XGBoost)
- SMOTE resampling improves model performance

## 🚀 Usage
1. Install required dependencies
2. Run cells sequentially in the notebook
3. Review model performance metrics in the final dataframe

## 📝 Notes
- Random state set to 42 for reproducibility
