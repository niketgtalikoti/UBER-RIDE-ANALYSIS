# 🚗 Uber Trip Analysis and Forecasting

## 📌 Project Overview
This project analyzes and forecasts Uber trip demand using real-world data from **New York City (Jan–Feb 2015)**. It combines **exploratory analysis**, **data visualization**, and **machine learning models** to uncover demand patterns and predict daily trip volumes. The results aim to help Uber optimize fleet allocation, improve service efficiency, and guide strategic decision-making.

---

## 🎯 Objectives
- Analyze trip trends and dispatch patterns across NYC
- Forecast future daily trip volumes using ML models
- Recommend data-driven operational improvements

---

## 🗃️ Dataset Summary
- **Source**: Uber NYC Open Data (Jan–Feb 2015)
- **Records**: Daily trip data
- **Key Columns**:
  - Date
  - Base Number (dispatch center)
  - Trips
  - Active Vehicles

---

## 🧪 Tools & Technologies
- **Languages**: Python
- **Libraries**: Pandas, Scikit-learn, XGBoost, Plotly
- **Platform**: Jupyter Notebook

---

## 📊 Exploratory Data Analysis
- **Trip Volume Patterns**:
  - Peak demand on **Fridays**, lowest on **Sundays**
  - **Mid-January growth** in trip volume; consistent rise into February
- **Base-wise Performance**:
  - Base **B02764** handled ~2M trips — most active hub
  - B02617, B02682 — moderate activity
- **Trip & Vehicle Correlation**:
  - Strong relationship between **active vehicles** and **trip counts**

---

## 🔁 Machine Learning Models

### 1. Random Forest Regressor
- Features: Day, Month, Weekday, Base, Active Vehicles
- Output: Trip prediction
- Result: **Active Vehicles** was the most critical feature

### 2. XGBoost Regressor (Time Series Forecasting)
- Captured **seasonality** and **growth trends**
- Effective for **short-term prediction** (e.g., Feb 27, 2015)
- Detected anomalies (e.g., Feb 28 overprediction)

---

## 📌 Key Insights
- **Fridays** are high-volume days → surge pricing opportunity
- **B02764** is the dominant dispatch center
- **Active Vehicles** drive trip volume more than calendar features
- **Fleet size needs to scale** with weekday peaks

---

## 💡 Business Implications
- **Optimize fleet allocation** based on weekday and base trends
- **Lower wait times** by aligning driver supply with demand
- **Schedule drivers smartly** for high-demand windows
- **Improve profitability** through proactive resource planning

---

## 📈 Performance Metrics
- RMSE and R² used to evaluate prediction accuracy
- Time series model successfully forecasted weekday demand patterns

---

## 🧠 Conclusion
This project demonstrates how Uber can use historical trip and base data to predict demand, enhance fleet management, and reduce operational inefficiencies. By integrating ML forecasting and data visualization, Uber can proactively manage its on-demand service for better customer experience and operational excellence.

---

**Developed by**: [Niket Talikoti](https://linkedin.com/in/nikettalikoti)  
🔗 [GitHub Profile](https://github.com/niketgtalikoti)
