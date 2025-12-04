# 🛵 Swiggy Delivery Time Prediction – Experimentation

This repository contains all experimentation and research work for building a **delivery time (ETA) prediction system**, inspired by real food-delivery platforms like **Swiggy** and **Zomato**.

The purpose of this repo is to perform **data cleaning, feature engineering, EDA, model training**, and evaluate multiple machine learning approaches before deploying the final model in production.

---

## 🚀 Project Overview

The goal of this project is to predict **how long a food order will take to be delivered**, based on:

- Delivery partner information  
- Restaurant & customer locations  
- Order timestamps  
- Weather & traffic conditions  
- Order type and vehicle type  

This repository includes **all Jupyter notebooks and experimentation code** used before selecting and deploying the final production model.

---

## 🧹 Data Preprocessing & Cleaning

Key preprocessing steps include:

- Handling missing or inconsistent values  
- Converting and normalizing timestamps  
- Engineering new features such as **Haversine distance**  
- Encoding all categorical variables  
- Scaling numerical features  
- Detecting invalid or abnormal entries (coordinates, ratings, age, etc.)  

---

## 📊 Exploratory Data Analysis (EDA)

Extensive EDA was performed to understand real-world delivery patterns:

- Delivery partner performance trends  
- Traffic density vs delivery time  
- Weather impact on ETA  
- City-wise performance analysis  
- Correlation between features  
- Target variable distribution analysis  
- Missing data visualization & patterns  

These insights helped guide feature engineering and model selection.

---

## 🧪 Model Experimentation

Multiple ML algorithms were trained and compared, including:

- **LightGBM**  
- **CatBoost**  
- **Support Vector Machine (SVM)**  
- **XGBoost Regressor**  
- **Random Forest Regressor**  

All models were evaluated based on:

- **MAE (Mean Absolute Error)**  
- **RMSE (Root Mean Squared Error)**  
- **R² Score**  

The best-performing models (LightGBM + CatBoost) were later fine-tuned and used in the **production ensemble model**.

---

## 🔗 Important Project Links

### ✅ **Final Production Repository (FastAPI, Docker, AWS Auto Scaling Deployment)**  
https://github.com/apoorvtechh/delivery_time_estimator  

### 📝 **Project Synopsis (Detailed Write-up + Architecture Explanation)**  
https://github.com/apoorvtechh/synopsis_eta  

---

