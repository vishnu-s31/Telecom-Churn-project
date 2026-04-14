# 📊 Telecom Churn Prediction using Machine Learning

![Telecom Churn Banner](Telecom-Churn-main/finger-pressing-red-icon.jpg)

## 🚀 Project Overview
Customer churn is a critical challenge in the telecom industry, where losing customers directly impacts revenue and growth. This project aims to build a robust machine learning model to predict whether a customer is likely to churn based on their demographic details, service usage patterns, and account information.

The solution helps businesses proactively identify at-risk customers and implement targeted retention strategies, ultimately improving customer satisfaction and reducing revenue loss.

---

## 🎯 Problem Statement
Telecom companies face high competition, making customer retention a top priority. The objective of this project is to:

- Identify key factors influencing customer churn  
- Develop predictive models to classify churn vs non-churn customers  
- Provide actionable insights to support business decision-making  

---

## 📊 Dataset Description
The dataset contains customer-level information including:

- **Demographics**: Gender, Senior Citizen, Partner, Dependents  
- **Account Information**: Tenure, Contract Type, Payment Method  
- **Services Subscribed**: Internet Service, Online Security, Streaming Services  
- **Billing Details**: Monthly Charges, Total Charges  
- **Target Variable**: Churn (Yes/No)  

---

## 🔍 Exploratory Data Analysis (EDA)
Performed in-depth EDA to understand patterns and relationships:

- Analyzed class imbalance in churn distribution  
- Identified strong correlations between churn and contract types  
- Visualized customer behavior based on tenure and monthly charges  
- Detected trends showing higher churn among short-term users  

Key findings:
- Customers with **month-to-month contracts** are more likely to churn  
- Higher **monthly charges** increase churn probability  
- Customers with **longer tenure** tend to stay  

---

## 🧹 Data Preprocessing
- Handled missing and inconsistent values  
- Encoded categorical variables using label/one-hot encoding  
- Scaled numerical features for better model performance  
- Applied **SMOTE (Synthetic Minority Oversampling Technique)** to handle class imbalance  

---

## 🤖 Model Development
Multiple machine learning models were trained and evaluated:

- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  

### Model Optimization:
- Hyperparameter tuning  
- Cross-validation  
- Feature importance analysis  

---

## 📈 Evaluation Metrics
Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

Special focus was given to **Recall**, as identifying churn customers is more critical than overall accuracy.

---

## 🏆 Results & Performance
- Achieved strong predictive performance with ensemble models  
- Improved recall using class balancing techniques (SMOTE)  
- Random Forest / XGBoost performed best in capturing churn patterns  

---

## 💡 Business Insights
- Customers on **short-term contracts** are high-risk  
- **High billing customers** are more likely to churn  
- Lack of additional services (like online security) increases churn probability  

---

## 🔧 Tools & Technologies
- **Python**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models  
- **XGBoost** – Advanced boosting algorithm  
- **Jupyter Notebook** – Development environment  

---

## ▶️ How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
