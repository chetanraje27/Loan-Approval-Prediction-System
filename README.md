# 🏦 Loan Approval Prediction System

This project implements an automated system to predict the eligibility of a loan applicant using various Machine Learning algorithms.  
The goal is to provide a faster and more accurate decision-making process for financial institutions.

---

## 📌 Features

### 🔹 Data Preprocessing
- Manual handling of missing values  
- Outlier detection using the IQR method  
- Label Encoding for categorical variables  

### 🔹 Feature Engineering
Created 8 new features to improve model performance, including:
- `Income_to_Loan_Ratio`
- `EMI`
- `DTI_Ratio`
- Additional derived financial indicators  

### 🔹 Class Balancing
- Implemented oversampling to handle target imbalance  
- Approval Rate in dataset: **~68%**

### 🔹 Algorithms Used
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Trees  
- Deep Learning Approaches  

---

## 📊 Dataset Information

- **Total Records:** 614 applicants  
- **Total Features:** 13  
- **Target Variable:** `Loan_Status (Y/N)`

### Key Features:
- Gender  
- Married  
- Education  
- ApplicantIncome  
- LoanAmount  
- Credit_History  
- Property_Area  

---

## 🚀 Deployment Readiness

This project includes a comprehensive evaluation framework:

### 📈 Evaluation Metrics
- Accuracy  
- F1-Score  
- Confusion Matrix  

### 📊 Visualizations
- Decision Boundary Plots  
- Clustering Analysis (Elbow Method)  
- Model Comparison Graphs  

### ✅ Status
**Production-Ready** with an established end-to-end data pipeline.

---

## 🛠️ Requirements

Install the required libraries:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

### Install via pip:

```bash
pip install -r requirements.txt
