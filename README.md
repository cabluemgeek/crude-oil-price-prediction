# The Use of Machine Learning in Forecasting Crude Oil Prices
---

## 📖 Project Overview
Crude oil is a strategic and essential resource for Algeria, forming the backbone of its **economy (19% of GDP)**, **exports (93%)**, and **budget revenues (75%)**. Due to its global and national importance, accurate oil price forecasting is crucial for effective economic planning and risk mitigation.

This project investigates the use of **Machine Learning (ML)** models to forecast crude oil prices and evaluates their performance compared to traditional approaches. We explore how **individual**, **hybrid**, and **deep learning** models perform on datasets of varying granularity (daily and monthly), and examine how dataset **size** and **feature richness** impact forecasting accuracy.

---

# 🎯 Problem Statement

Traditional econometric models often struggle with the **nonlinear and volatile** nature of oil prices. ML techniques have shown promise in handling such complexity.

> **Core Question:**  
> _How do different machine learning models and dataset characteristics influence the accuracy of crude oil price forecasts, and which approaches yield the most reliable predictions?_

### 📌 Secondary Questions

- Do hybrid machine learning models outperform individual models in forecasting crude oil prices?
- Do machine learning models perform better on larger datasets?
- Does the number of input features significantly impact forecasting accuracy?

### 📌 Hypotheses

- Hybrid ML models will outperform individual models.
- Larger datasets may improve the accuracy of some models.
- More relevant features will increase model performance.

---

## 📊 Methodology


- **Dataset:** Daily and monthly crude oil prices
- **Models used:**  
  - *Individual:* `SVR`, `Random Forest`, `XGBoost`, `LSTM`, `CNN`  
  - *Hybrid:* `Random Forest + XGBoost`, `CNN + LSTM`
- **Tasks:**
  - Data preprocessing & feature engineering
  - Training and testing models on both datasets
  - Comparing models by performance across time granularity and architecture

---

## 🔍 Data Source

- [Kaggle - Crude Oil Historical Prices Dataset](https://www.kaggle.com/)
- Additional sources:
  - U.S. EIA
  - World Bank
  - IMF

---

## 🛠 Technologies Used

- Python (pandas, numpy, scikit-learn, TensorFlow)
- Jupyter Notebooks
- matplotlib & seaborn (visualizations)
- Git / GitHub

---

## 📌 Key Results

- **Hybrid models** (CNN+LSTM, RF+XGBoost) showed **higher forecasting accuracy** than standalone models.
- Larger datasets generally improved performance, especially for tree-based models.
- Feature richness significantly influenced deep learning models' ability to generalize.

---











