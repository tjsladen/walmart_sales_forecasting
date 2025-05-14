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
- Python (Pandas, Matplotlib, Seaborn, Plotly, Prophet, XGBoost, Numpy, SKLearn, Shap and statsmodels)
- Jupyter Notebook
- Visualised and tested with cross-validation
- HTML export available for review

## 🧠 Insights
- Seasonal trends dominate sales variation
- Several stores showed forecast-resistant behavior, likely due to missing external variables
- Grouped stores by forecasting difficulty using K-Means

## 🔗 View the Project
- 📄 **Download Full HTML Report** (plots + visuals): [Download HTML](https://github.com/tjsladen/walmart_sales_forecasting/blob/aadf0999611f3b8a27167ccff0a31a3706de872b/Walmart_report.html) Then click download raw file (17.2MB)
- 🌐 **Interactive View (nbviewer)**: [View on nbviewer.org](https://nbviewer.org/github/tjsladen/walmart_sales_forecasting/blob/8461981236a90963e52b68b989d65e7b5f4a512f/Walmart_sales_codeV.ipynb)

## 🗂️ Dataset
Original data from [Walmart Store Sales Prediction - Regression Problem](https://www.kaggle.com/datasets/yasserh/walmart-dataset)
