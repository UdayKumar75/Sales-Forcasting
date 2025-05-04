# 📈 Sales Forecasting Using ARIMA and Prophet

This project focuses on time series forecasting of monthly sales using two popular techniques — **ARIMA** and **Facebook Prophet**. The objective is to model historical sales data and forecast future sales for better business planning and decision-making.

---

## 🗂️ Project Structure

├── train.csv # Sales data with order dates
├── sales_forecasting.ipynb # Jupyter notebook with full analysis and models
├── README.md # Project overview and documentation

---

## 📊 Dataset

The dataset (`train.csv`) contains historical sales records with the following relevant columns:

- `Order Date`: The date of sale (day-first format)
- `Sales`: Sales amount for each transaction

Data is resampled to **monthly frequency** (`MS`) for time series modeling.

---

## 🔧 Tools & Libraries Used

- **Python 3.12**
- `pandas`, `matplotlib` – Data manipulation and visualization
- `statsmodels` – ARIMA model
- `prophet` – Facebook Prophet model for seasonal time series forecasting
- `scikit-learn` – MAPE for model evaluation

---

## 📌 Forecasting Techniques

### 🔹 ARIMA (AutoRegressive Integrated Moving Average)
- Classical statistical model ideal for short-term forecasting.
- Simple (1,1,1) configuration used (can be tuned).
- Visual forecast plotted for 12 months ahead.

### 🔹 Prophet (by Facebook)
- Handles trends, seasonality, and holidays out of the box.
- Automatically decomposes time series components.
- Forecast extended for next 12 months.
- Plotted with confidence intervals.

---

## 📈 Results

- Forecasts generated from both models for 12 months into the future.
- **MAPE** (Mean Absolute Percentage Error) used to compare Prophet predictions against actual recent data.
- Visualizations help interpret forecast accuracy and trends.

---

## 📷 Sample Output Plots

- Monthly Sales Trend
- ARIMA Forecast vs Actual
- Prophet Forecast with Confidence Intervals

---
