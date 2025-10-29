# Sentinel-Financial-AI - Intelligent Financial Risk Assessment Platform

## 🚀 Project Overview

**EMIPredict AI** is a **FinTech and Banking** platform that uses **Machine Learning** and **MLflow** to deliver intelligent financial risk assessment and **EMI prediction**.  
It predicts both **EMI eligibility** (classification) and **maximum EMI amount** (regression) using 400,000 real-world financial records and 22 features.

---

## 🎯 Problem Statement

People often struggle with EMI payments due to **poor financial planning** and **inadequate risk assessment**.  
This project solves that problem by providing **data-driven insights** for better loan decisions.

### ✅ The Platform Delivers:
- Dual ML Solutions: **Classification (Eligibility)** & **Regression (Max EMI Amount)**
- **MLflow integration** for model tracking & comparison  
- **Streamlit Cloud Deployment** for real-time accessibility  
- **CRUD operations** for managing financial data  
- Real-time financial risk assessment on **400K+ records**

---

## 🧩 Skills Gained

**Python | Streamlit | MLflow | Machine Learning | Feature Engineering | Data Preprocessing | Classification | Regression | FinTech Analytics**

---

## 💼 Business Use Cases

### 🏦 Financial Institutions
- Automate loan approval and cut underwriting time by 80%
- Enable risk-based pricing models
- Real-time EMI eligibility for in-branch customers

### 📱 FinTech Companies
- Instant EMI eligibility checks on digital lending apps
- Automated risk scoring for loan applications

### 💰 Banks & Credit Agencies
- Data-driven loan recommendations  
- Default prediction and portfolio risk management

### 👩‍💼 Loan Officers & Underwriters
- AI-powered decision support for loan approvals  
- Real-time model monitoring and historical performance tracking

---

## 🧠 Project Approach

### **Step 1: Data Loading & Preprocessing**
- Load 400K financial records  
- Handle missing values, inconsistencies, and duplicates  
- Train-test-validation split creation  

### **Step 2: Exploratory Data Analysis**
- Analyze eligibility distribution and correlations  
- Generate business insights and visualizations  

### **Step 3: Feature Engineering**
- Derive ratios (debt-to-income, affordability, etc.)
- Encode categorical and scale numerical features  

### **Step 4: Machine Learning Model Development**

#### 🧩 Classification Models (EMI Eligibility)
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  
- *(Optional: SVC, Decision Tree, Gradient Boosting)*  
**Metrics:** Accuracy, Precision, Recall, F1, ROC-AUC

#### 📈 Regression Models (Max EMI Amount)
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  
- *(Optional: SVR, Decision Tree Regressor)*  
**Metrics:** RMSE, MAE, R², MAPE  

### **Step 5: MLflow Integration**
- Experiment tracking for all models  
- Parameter and metric logging  
- Artifact and model version management  
- Model registry for production-ready tracking  

### **Step 6: Streamlit Application Development**
- Multi-page UI  
- Real-time prediction  
- MLflow dashboard integration  
- CRUD-based data management  

### **Step 7: Cloud Deployment**
- Deployment on **Streamlit Cloud**  
- GitHub CI/CD automation  
- Responsive UI for all devices  

---

## 🧱 System Architecture

```plaintext
Dataset (400K Records)
       ↓
Data Cleaning & Preprocessing
       ↓
Feature Engineering & EDA
       ↓
ML Model Training + MLflow Tracking
       ↓
Model Evaluation & Selection
       ↓
Streamlit Web App
       ↓
Streamlit Cloud Deployment
       ↓
Production-Ready Financial Risk Platform

---

## 🧩 Architecture Layers

| Layer                | Description                                                      |
| -------------------- | ---------------------------------------------------------------- |
| **Data Layer**       | Structured financial datasets                                    |
| **Processing Layer** | Data cleaning, feature engineering, and ML pipelines             |
| **Model Layer**      | ML models with MLflow tracking and versioning                    |
| **App Layer**        | Streamlit-based user interface for interaction and visualization |
| **Deployment Layer** | Streamlit Cloud hosting with CI/CD integration via GitHub        |

---

## 📊 Dataset Overview

| Attribute     | Details                                                                      |
| ------------- | ---------------------------------------------------------------------------- |
| **Records**   | 400,000 financial profiles                                                   |
| **Features**  | 22 financial and demographic variables                                       |
| **Targets**   | 2 (Classification + Regression)                                              |
| **Scenarios** | 5 EMI types – E-commerce, Home Appliances, Vehicle, Personal Loan, Education |

---

## 🎯 Target Variables

🧮 Classification

emi_eligibility → Eligible | High_Risk | Not_Eligible

💸 Regression

max_monthly_emi → Continuous EMI amount (₹500 – ₹50,000 INR)


