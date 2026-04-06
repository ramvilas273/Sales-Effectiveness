# 📈 Sales Effectiveness Prediction using Machine Learning

## 🚀 Overview
This project focuses on improving sales effectiveness by predicting lead quality using machine learning techniques. The goal is to help businesses identify high-potential leads and improve conversion rates through data-driven decision-making.

---

## 🏢 Business Case
FicZon Inc. is an IT solutions provider offering both on-premises and SaaS-based products. The company primarily generates leads through digital channels such as its website.

However, sales performance has declined due to:
- Increased market competition  
- Dependency on manual lead categorization  
- Inconsistent lead quality assessment  

To address this, the company aims to use **Machine Learning** to automatically classify leads into:
- High Potential  
- Low Potential  

---

## 🎯 Project Goals
1. Perform data analysis to understand sales effectiveness  
2. Build a machine learning model to predict lead category  
3. Improve lead prioritization and conversion rates  

---

## 📊 Dataset Description

### 🔑 Features:
- **Created**: Date and time when the lead was generated  
- **Product_ID**: Unique product identifier  
- **Source**: Lead origin (website, phone call, email, etc.)  
- **Mobile**: Contact number of the lead  
- **Email**: Email address of the lead  
- **Sales_Agent**: Agent responsible for the lead  
- **Location**: Lead's geographic location  
- **Delivery_Mode**: Mode of product delivery  
- **Status**: Current status of the lead (target variable)  

---

## 🔍 Exploratory Data Analysis (EDA)
- Analyzed lead distribution across different sources  
- Identified patterns in lead conversion  
- Explored relationship between sales agents and performance  
- Detected missing values and inconsistencies  

📌 **Key Insights:**
- Leads from certain sources have higher conversion rates  
- Sales agent performance varies significantly  
- Location and delivery mode impact lead quality  

---

## ⚙️ Data Preprocessing
- Handled missing values  
- Encoded categorical variables  
- Removed irrelevant features  
- Split data into training and testing sets  

---

## 🤖 Model Building
Applied multiple classification algorithms:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost (Best Model)  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Neural Network  

---

## 📈 Model Evaluation

### 📊 Accuracy Comparison:
- **XGBoost**: 74.51% (Best)  
- **Random Forest**: 73.50%  
- **Decision Tree**: 69.03%  
- **KNN**: 66.60%  
- **SVM / Logistic Regression**: 63.62%  
- **Neural Network**: 59.97%  
- **Naive Bayes**: 55.17%  

📌 XGBoost performed best due to its ability to handle complex data patterns.

---

## ⚙️ Hyperparameter Insights
- XGBoost used optimized learning rate (~0.74)  
- Random Forest used ~743 estimators  
- SVM used regularization parameter (C ≈ 0.735)  
- Decision Tree depth optimized to reduce overfitting  

---

## 📊 Key Learnings
- Ensemble models (XGBoost, Random Forest) outperform simpler models  
- Proper hyperparameter tuning significantly improves performance  
- Data preprocessing plays a critical role in model success  

---

## 📌 Conclusion
- Machine Learning can significantly improve lead classification  
- XGBoost is the most effective model for this problem  
- Automated lead scoring helps increase sales efficiency  
- Data-driven insights can enhance business decision-making  

---

## 🔮 Future Work
- Improve model accuracy with advanced tuning  
- Deploy model using Flask or Streamlit  
- Integrate with CRM systems for real-time predictions  
- Perform feature engineering for better insights  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn, XGBoost  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 🙋‍♂️ About Me
Aspiring Data Scientist with strong skills in Python, SQL, and Machine Learning, experienced in building predictive models and delivering business insights.

---

## ⭐ If you like this project
Give it a star ⭐ on GitHub!