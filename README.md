# 🇸🇦 Saudi Economic Pulse: ETL Pipeline & Time Series Forecasting

![Tableau](https://img.shields.io/badge/Tableau-Public-orange?style=flat&logo=tableau)
![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat&logo=python)
![Econometrics](https://img.shields.io/badge/Model-ARIMA-green)

An end-to-end data analytics and econometric forecasting project designed to extract, clean, and model Saudi Arabia’s macroeconomic retail metrics—specifically comparing **Point of Sales (POS)** transactions against **E-Commerce** trends.

---

## 📊 Interactive Dashboard
🔗 **[View the Live Tableau Dashboard Here](https://public.tableau.com/app/profile/mashaer.alanizy/viz/SaudiEconomicPulseDashboard/MarketShare_1#2)**

---

## 📌 Project Overview & Workflow

This project follows a structured 4-stage methodology:

1. **ETL Pipeline (Python):** 
   * Standardized date ranges and formats ($YYYY-MM$).
   * Handled missing values, outliers, and unified data from SAMA & GASTAT sources into a master DataFrame.
2. **Econometric Forecasting (ARIMA):**
   * Performed Time Series Analysis checking for stationarity and seasonality.
   * Fitted an **ARIMA** model on historical sales data to predict upcoming quarterly trends.
3. **Data Visualization (Tableau):**
   * Built interactive dashboards featuring **POS vs. E-Commerce** growth comparison and market share trends.

---

## 📂 Repository Structure

* `saudi_economic_pulse_clean.csv`: Cleaned dataset containing historical and forecasted metrics.
* `Untitled0.ipynb`: Jupyter Notebook containing Python code for ETL and ARIMA modeling.
* `README.md`: Project documentation.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing:** `pandas`, `numpy`
* **Modeling & Forecasting:** `statsmodels` (ARIMA), `pmdarima`
* **Visualization:** Tableau Public

---

## 👤 Author
**Mashaer Al-Anazi**  
*Economic Data Analyst & Business Development Specialist*  
[GitHub Profile](https://github.com/Mashaer11)
