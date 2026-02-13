# Time-Series-Forecasting-Sales-Trend-Prediction-Task-16
This project performs time-series forecasting on sales data to analyze trends, seasonality, and predict future sales using Python. The goal is to help businesses plan inventory, budgeting, and demand forecasting based on historical patterns.

# Objective
 - Analyze historical sales trend
 - Identify seasonality patterns
 - Apply forecasting model
 - Predict next period sales
 - Evaluate model performance

 # Tools & Technologies
  - Python
  - Pandas & Matplotlib
  - Statsmodels (Exponential Smoothing)
  - Scikit-learn (MAE calculation)

# Dataset
 - Store Item Demand Forecasting Dataset
 - Columns used:
     - date
     - sales
 - Data was aggregated to monthly level for forecasting.

# Steps Performed
 1. Converted date column to datetime format.
 2. Aggregated daily sales into monthly totals.
 3. Visualized sales trend.
 4. Checked seasonality using rolling mean.
 5. Split dataset into train and test based on time.
 6. Applied Exponential Smoothing forecasting model.
 7. Predicted next 6 months sales.
 8. Calculated error metrics (MAE & MAPE).
 9. Exported forecast results to CSV.

# Key Insights
 - Sales show a strong upward growth trend.
 - Clear yearly seasonality pattern observed.
 - Forecast predicts continued increase in demand.
 - Model performs reasonably well with acceptable error rate.

# Model Used
 - Exponential Smoothing (Holt-Winters method)
 - Why?
     - Suitable for trend-based time-series
     - Captures level and trend components
     - Simple and effective for business forecasting

# Project Files
 - task16_forecasting.ipynb → Python notebook
 - forecast_output.csv → Predicted sales values
 - forecast_report.docx → Business summary report
 - README.md → Project documentation

# Learning Outcomes
 - Understanding time-series concepts
 - Trend and seasonality analysis
 - Forecast model implementation
 - Error metric evaluation (MAE, MAPE)
 - Business interpretation of forecasts

# Conclusion
 This project demonstrates how time-series forecasting can support data-driven business planning by predicting future sales trends using historical data patterns.
