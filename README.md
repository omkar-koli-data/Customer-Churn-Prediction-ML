# 📊 Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

This project predicts whether a bank customer is likely to churn using Machine Learning.

The project follows an end-to-end Machine Learning workflow including data cleaning, exploratory data analysis, feature engineering, data preprocessing, model training, model evaluation, feature importance analysis, and customer churn prediction.

## 🎯 Objectives

- Understand customer churn patterns
- Perform data cleaning and exploratory data analysis
- Prepare customer data for Machine Learning
- Build classification models
- Compare model performance
- Identify important features affecting churn
- Predict churn probability for a new customer

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🤖 Machine Learning Models

Three classification models were trained:

- Logistic Regression
- Random Forest
- XGBoost

## 📈 Model Performance

| Model | Accuracy | ROC-AUC |
|---|---:|---:|
| Logistic Regression | 80.8% | 0.775 |
| Random Forest | 86.3% | 0.852 |
| XGBoost | 86.7% | 0.867 |

## 🔍 Feature Importance

The XGBoost model identified the following features among the most important for its predictions:

- Products Number
- Active Member
- Age
- Country
- Balance

Feature importance indicates how useful features were to the trained model's predictions and does not by itself establish causation.

## 💡 Sample Prediction

The trained XGBoost model was used to predict churn for a sample customer.

- Predicted Churn: 0
- Churn Probability: 25.37%

## 📂 Project Files

- `Customer_Churn_Prediction.ipynb` — Complete Machine Learning notebook
- `Bank Customer Churn Prediction.csv` — Dataset used for the project

## 🚀 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Categorical Encoding
6. Train-Test Split
7. Feature Scaling
8. Model Training
9. Model Evaluation
10. ROC-AUC Analysis
11. Feature Importance Analysis
12. New Customer Churn Prediction

## 📌 Conclusion

This project demonstrates an end-to-end Machine Learning workflow for customer churn prediction using banking customer data.

The evaluated models achieved different levels of performance, with XGBoost producing 86.7% accuracy and a 0.867 ROC-AUC on the test set. The project also demonstrates how model predictions can be combined with feature importance analysis and churn probability estimation to support customer retention analysis.
