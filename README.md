#  Heart Disease Prediction & Clinical Risk Analytics

---

## 📌 Overview

This project focuses on predicting the presence of heart disease using machine learning techniques and healthcare analytics. Using the UCI Cleveland Heart Disease Dataset, a complete data science workflow was implemented, including data preprocessing, exploratory data analysis (EDA), model development, performance evaluation, and dashboard visualization.

The objective is to identify patients at risk of heart disease and provide meaningful clinical insights through predictive analytics.

---

## 🎯 Project Objectives

- Predict the presence of heart disease using clinical patient data.
- Perform data cleaning and preprocessing.
- Analyze relationships between medical attributes and disease occurrence.
- Compare multiple machine learning models.
- Identify the most influential risk factors.
- Develop an interactive Tableau dashboard for visualization.

---

## 📊 Dataset Information

**Dataset:** UCI Cleveland Heart Disease Dataset

- Total Records: 303 Patients
- Features: 13 Clinical Features + 1 Target Variable
- Problem Type: Binary Classification

### Key Features

- Age
- Sex
- Chest Pain Type (CP)
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Exercise-Induced Angina
- Thalassemia
- Number of Major Vessels
- Target (Heart Disease Presence)

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Missing Value Imputation (Median)
- Target Variable Conversion to Binary Classification
- Outlier Removal using IQR Method
- One-Hot Encoding of Categorical Features
- Feature Scaling using StandardScaler

---

## 📈 Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset and identify meaningful clinical patterns.

### Analyses Performed

- Heart Disease Distribution
- Age vs Heart Disease
- Chest Pain Analysis
- Heart Rate Analysis
- Cholesterol Analysis
- Correlation Heatmap
- Feature Correlation with Target

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

| Model | Accuracy |
|---------|---------|
| Logistic Regression | **87.72%** |
| Random Forest | 77.19% |
| SVM | 73.68% |
| Decision Tree | 70.18% |

### 🏆 Best Model: Logistic Regression

- Accuracy: **87.72%**
- Precision: **87.50%**
- Recall: **84.00%**
- F1 Score: **85.71%**
- ROC-AUC Score: **0.936**

---

## 📉 Confusion Matrix

| Actual / Predicted | No Disease | Disease |
|-------------------|-----------|----------|
| No Disease | 29 | 3 |
| Disease | 4 | 21 |

---

## 🔍 Top Risk Factors Identified

1. Chest Pain Type (CP)
2. Thalassemia
3. Gender
4. Number of Major Vessels (CA)
5. Exercise-Induced Angina

---

## 📊 Tableau Dashboard

The project includes an interactive Tableau dashboard featuring:

- Patient Summary KPIs
- Disease Distribution
- Age Analysis
- Chest Pain Analysis
- Cholesterol Analysis
- Heart Rate Analysis
- Model Performance Comparison
- Clinical Risk Insights

---

## 🛠️ Technologies Used

### Programming & Machine Learning
- Python
- Pandas
- NumPy
- Scikit-Learn

### Visualization
- Matplotlib
- Seaborn
- Tableau

### Development Environment
- Google Colab

---

## 🚀 Project Outcomes

✔ Developed an end-to-end machine learning pipeline for heart disease prediction.

✔ Achieved **87.72% accuracy** and **0.936 ROC-AUC** using Logistic Regression.

✔ Identified clinically relevant risk factors associated with heart disease.

✔ Built an interactive Tableau dashboard for healthcare analytics and decision support.

---

## 🔮 Future Enhancements

- Deploy as a web application
- Implement XGBoost and LightGBM
- Add Explainable AI (SHAP/LIME)
- Use larger healthcare datasets

---

## 👨‍💻 Author

**Soumya Ghosh**  
Biomedical Engineering Undergraduate  
National Institute of Technology Raipur

---
