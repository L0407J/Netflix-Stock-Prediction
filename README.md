Netflix Stock Price Forecasting using Facebook Prophet
📌 Overview

This project forecasts Netflix (NFLX) daily closing stock prices using the Facebook Prophet time-series model. The objective was to analyze historical trends and generate future predictions with confidence intervals.

🎯 Objective

Forecast Netflix closing prices using historical data (2002–2025)

Apply Prophet to capture trend and seasonality

Generate interpretable future predictions

📊 Dataset

Source: Kaggle (Netflix Stock Data)

5,817 daily records

Features: Date, Open, High, Low, Close, Volume

Target Variable: Close price

🛠 Tools Used

Python

Google Colab

Pandas, NumPy

Matplotlib

Facebook Prophet

🔍 Key Steps

Data cleaning & preprocessing

Exploratory Data Analysis (trend visualization & statistics)

Prophet model training

90–365 day future forecasting

Confidence interval analysis

📈 Results

Captured long-term upward trend

Identified volatility periods (e.g., pandemic years)

Generated prediction ranges (yhat, yhat_lower, yhat_upper)

Visualized forecast with 95% confidence interval

⚠ Limitations

Does not account for external factors (earnings, news, macroeconomic indicators)

Includes non-trading days in predictions

🚀 Future Improvements

Compare with ARIMA & LSTM

Add sentiment analysis

Incorporate macroeconomic variables

📂 Skills Demonstrated

Time-Series Forecasting | Financial Data Analysis | Prophet Modeling | Data Visualization | Business Interpretation
