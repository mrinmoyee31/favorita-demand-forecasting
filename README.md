# Retail Demand Forecasting using XGBoost and LSTM

An end-to-end demand forecasting project built using the Corporación Favorita Grocery Sales dataset. The objective is to predict future product demand using machine learning and deep learning techniques and evaluate their effectiveness for retail inventory planning.

---

## Business Problem

Accurate demand forecasting is critical for inventory management, replenishment planning, and supply chain efficiency. Poor forecasts can lead to stockouts, excess inventory, and increased operational costs.

This project explores machine learning and deep learning approaches to forecast daily retail sales and compares their performance using industry-standard forecasting metrics.

---

## Dataset

**Corporación Favorita Grocery Sales Forecasting**

Source:
https://www.kaggle.com/competitions/favorita-grocery-sales-forecasting

The dataset contains:

- Daily sales transactions
- Product family information
- Store metadata
- Promotion information
- Holiday events
- Oil price data

---

## Project Objectives

- Perform exploratory data analysis to identify trends, seasonality, and demand patterns.
- Build a machine learning forecasting baseline using XGBoost.
- Develop a deep learning forecasting model using LSTM.
- Compare forecasting performance across models.
- Visualize forecasts and model performance through an interactive dashboard.
- Extend the project with inventory optimization techniques.

---

## Models

### Machine Learning

- XGBoost

### Deep Learning

- LSTM (Long Short-Term Memory Network)

### Future Enhancements

- Temporal Fusion Transformer (TFT)
- Inventory Optimization Module
- Automated Forecast Monitoring

---

## Evaluation Metrics

The models will be evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

---

## Project Structure

```text
retail-demand-forecasting/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_XGBoost_Model.ipynb
│   └── 03_LSTM_Model.ipynb
│
├── src/
│   ├── preprocessing.py
│   └── models.py
│
├── app/
│   └── streamlit_app.py
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- TensorFlow / Keras
- Matplotlib
- Streamlit

---

## Current Status

🚧 Work in Progress

### Roadmap

- [x] Repository Setup
- [x] Exploratory Data Analysis
- [ ] Data Cleaning
- [ ] Feature Engineering
- [ ] XGBoost Baseline Model
- [ ] LSTM Forecasting Model
- [ ] Model Comparison
- [ ] Streamlit Dashboard
- [ ] Inventory Optimization Module

---

## Expected Outcomes

- Understand retail demand drivers.
- Compare machine learning and deep learning forecasting approaches.
- Quantify forecasting accuracy improvements.
- Demonstrate an end-to-end forecasting workflow suitable for real-world supply chain applications.

---

## Author

**Mrinmoyee Hawladar**

Data Scientist | Machine Learning | Forecasting & Supply Chain Analytics

Email: mrinmoyeehawladar@gmail.com
