# 🔌 CSE445 Machine Learning Project: Zone-Wise Electricity Demand Prediction

## 📍 Overview
This project tackles a critical challenge faced by the Bangladesh Power Development Board (BPDB): how to accurately forecast electricity demand **zone by zone** across the country. As Bangladesh’s electricity consumption rises—especially in urban and industrial areas—inefficient distribution often leads to **unplanned load shedding and power shortages**.

We propose a machine learning-based solution that leverages historical electricity usage data (March 2021 – March 2025), weather patterns, supply disruptions, and regional characteristics to **predict demand at a more granular, regional level**.

---

## 🎯 Objectives
- Predict electricity demand for each zone in Bangladesh.
- Improve power distribution efficiency and reduce mismatches in supply.
- Support grid operators and planners with accurate, interpretable forecasts.

---

## 🧠 Machine Learning Approach

### ✅ Data Sources
- Historical electricity demand and supply data from BPDB.
- Weather conditions and reported supply shortages.

### ✅ Key Steps
1. **Data Preprocessing**: Cleaning, transforming, and engineering features from raw data.
2. **Exploratory Data Analysis (EDA)**: Understanding zone-wise patterns and correlations.
3. **Model Training**: Evaluated multiple supervised learning models:
   - Linear Regression
   - Decision Tree
   - Random Forest
   - XGBoost
   - SVR
   - KNN
4. **Ensemble Methods**:
   - Voting Regressor
   - Custom Averaging
5. **Model Evaluation**: Metrics like MAE, RMSE, and R².
6. **Interpretability**: LIME was used to explain predictions and improve model trust.

---

## 📊 Results Summary
- **Linear Regression** consistently delivered the best results across all zones, proving that even simpler models can be powerful with good data.
- **Ensemble methods** (Voting Regressor and Custom Averaging) improved generalization and robustness.
- Prediction was most accurate in **Dhaka, Comilla, and Khulna**, while zones like **Barisal and Rangpur** presented more variability and prediction difficulty.
- With **LIME**, we added transparency to our predictions—helping interpret which features most affected zone-wise demand.

---

## 🏁 Conclusion
Our work shows that **zone-wise electricity demand forecasting** using machine learning is not only feasible but highly beneficial. By enabling smarter energy distribution, this solution can help reduce blackouts, improve planning, and support the transition toward a more reliable and data-driven national grid.

This project lays the groundwork for future innovation in **smart grid management**, **real-time load balancing**, and **energy optimization** for Bangladesh and other developing nations.

---

## 📁 Repository Structure
