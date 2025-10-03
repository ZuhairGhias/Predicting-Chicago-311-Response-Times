# Predicting-Chicago-311-Response-Times

This repository contains code and documentation for our CS 412 (Fall 2025) group project.  
Our goal is to **predict the completion time of 311 service requests in Chicago**, using features such as request type, creation time, ZIP code, and historical backlog.

---

## Project Overview
- **Dataset:** [Chicago Data Portal – 311 Service Requests](https://data.cityofchicago.org/)  
- **Problem:** Estimate response time (`CLOSED_DATE - CREATED_DATE`) for service requests.  
- **Baselines:**
  1. Rolling 12-month average response time by ZIP code and service type  
  2. Linear/Non-linear regression using service request volume  
- **Proposed Method:** Gradient Boosted Decision Trees (e.g., scikit-learn `HistGradientBoostingRegressor`, XGBoost, or LightGBM)  

---

*This README was generated with the assistance of ChatGPT (OpenAI).*  
