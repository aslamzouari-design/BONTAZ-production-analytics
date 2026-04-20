# 🏭 TUNISTOOLS Production Analytics & Demand Forecasting

## 🎯 Problem Statement
Developing a complete end-to-end data analytics and Machine Learning pipeline for Bontaz Tunisia (Tier-1 automotive supplier) to optimize production forecasting and analyze OEE/TRS based on 6 years of daily production records.

## 🧠 Methodology
1. **Data Quality:** Outlier consensus detection (IQR + Z-Score + MAD).
2. **Industrial Analytics:** Pareto 80/20 analysis and KPI extraction.
3. **Machine Learning:** Engineering 20 temporal features and training XGBoost models with TimeSeriesSplit validation.

## 📊 Key Results
* **Data Volume:** Handled 114,259 daily production records (2020–2025).
* **Model Performance:** Achieved 14.7% MAPE on the test set using XGBoost.
* **Reliability:** Generated 2026 forecasts with Bootstrap 90% Confidence Intervals (N=200 resamples).
* **Insights:** Evaluated 76.7% global OEE and identified 20 machine×part combinations representing 80% of production.

## 💻 Tech Stack
* Python | Pandas | NumPy
* Scikit-Learn | XGBoost
* Matplotlib | Seaborn
