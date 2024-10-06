# Demand Forecasting and Customer Segmentation

## Overview
This project addresses two key aspects of retail analytics: **Customer Segmentation** and **Demand Forecasting**. It uses the **Dunnhumby dataset** for customer segmentation and the **Walmart sales dataset** for demand forecasting, applying statistical and machine learning models to generate insights and predictions.

## Customer Segmentation
- **Dataset**: Dunnhumby transactional data.
- **Methodology**:
  - Performed **RFM (Recency, Frequency, Monetary)** analysis to score customers.
  - Applied **K-Means clustering** to segment customers into groups based on purchasing behavior.
  - Conducted **Price Sensitivity** analysis using **price elasticity** to evaluate customer response to price changes.
- **Results**: Identified key customer segments and insights on price-sensitive groups using **Seaborn** for visualizations.

## Demand Forecasting
- **Dataset**: Walmart sales data.
- **Steps**:
  - Preprocessed and engineered features (e.g., time-based columns, lag features).
  - Applied **ARIMA** and **Auto-ARIMA** models for baseline predictions.
  - Built an **LSTM model** using **TensorFlow** to predict future sales.
- **Results**: Achieved refined sales forecasts, evaluated with loss functions.

## Tech Stack
- **Python** (Pandas, NumPy, Seaborn, scikit-learn, statsmodels, TensorFlow)
- **Jupyter Notebook** for running the analyses.

## Conclusion
The project provides actionable insights into customer segmentation and sales forecasting, helping optimize pricing strategies and inventory management through data-driven predictions.

---

This version delivers the necessary information for a GitHub README without overwhelming detail, fitting well for a concise project overview.
