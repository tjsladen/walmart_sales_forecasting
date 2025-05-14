# 🛒 Walmart Weekly Sales Forecasting

This project uses time series modeling to forecast weekly sales across 45 Walmart stores using Python and Prophet. It includes:

- Exploratory data analysis and store grouping by performance
- Seasonal decomposition and anomaly detection
- Forecasting using Facebook Prophet
- Evaluation using MAPE and cluster-based error insights
- Visualisations with Seaborn and Plotly

## 📈 Highlights
- MAPE between 0.02 and 0.1 across stores
- Custom visualisations of forecast uncertainty and anomalies
- SHAP and XGBoost used for feature relevance testing

## 🔍 Tools Used
- Python (Pandas, Matplotlib, Seaborn, Plotly, Prophet, XGBoost, Numpy, SKLearn (train/test split))
- Jupyter Notebook
- Visualised and tested with cross-validation
- HTML export available for review

## 🧠 Insights
- Seasonal trends dominate sales variation
- Several stores showed forecast-resistant behavior, likely due to missing external variables
- Grouped stores by forecasting difficulty using K-Means

## 🔗 View the Project

You can download and view the full interactive HTML version of the notebook here:

[Download HTML Version](https://github.com/tjsladen/walmart-sales-forecasting/raw/main/Walmart_sales.html)

## 🗂️ Dataset
Original data from [Walmart Store Sales Prediction - Regression Problem](https://www.kaggle.com/datasets/yasserh/walmart-dataset)
