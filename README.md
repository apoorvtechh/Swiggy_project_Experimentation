# 🛵 Swiggy Delivery Time Prediction – Experimentation

This repository contains all experimentation work for building a **delivery time (ETA) prediction system** inspired by real food-delivery platforms like Swiggy and Zomato.

The goal of this phase is to explore the dataset, engineer meaningful features, experiment with multiple ML models, and choose the best-performing approach for production deployment.

---

## 🚀 Project Overview

The project aims to predict how long a delivery will take based on:

- Delivery partner information  
- Restaurant & customer locations  
- Order timestamps  
- Weather and traffic conditions  
- Order type and vehicle type  

This repo includes **all experimentation notebooks** used before integrating the final model into the production API.

---

## 🧹 Data Preprocessing & Cleaning

- Handling missing or inconsistent values  
- Normalizing time formats (Order time, Pickup time, etc.)  
- Creating new features (e.g., Haversine distance)  
- Encoding categorical features  
- Scaling numerical variables  

---

## 📊 Exploratory Data Analysis (EDA)

- Delivery partner performance trends  
- Traffic density vs delivery time  
- Weather impact analysis  
- City-wise comparisons  
- Feature correlation heatmaps  
- Understanding distribution of target variable  

---

## 🧪 Model Experimentation

Multiple machine learning algorithms were trained and compared:

- **LightGBM**  
- **CatBoost**  
- **SVM**  
- **XGB**  
- **Random Forest**  

Each model was evaluated on:

- MAE, RMSE  
- R² Score  
- Training vs. inference speed  
- Stability and generalization  

---

## 🎯 Hyperparameter Tuning

Performed using:
 
-  Optuna
- Manual iterative tuning  
- MLflow experiment tracking  

The best results came from a **weighted ensemble** of LightGBM + CatBoost.

---

