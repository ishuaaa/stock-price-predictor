# stock-price-predictor
📈 Stock Price Predictor (Tesla) using Machine Learning

A simple machine learning project to predict Tesla (TSLA) stock prices using historical data and Logistic Regression , svc, XGB in Python.

🔍 Overview

This project demonstrates how machine learning can be applied to stock market data for price prediction. It focuses on Tesla’s stock and uses historical data to forecast future closing prices.

Key Features:
	•	Fetches historical stock data using yfinance
	•	Visualizes trends with moving averages and line charts
	•	Preprocesses data and applies feature scaling
	•	Trains and evaluates a Linear Regression model
	•	Compares predicted vs. actual prices using graphs
	•	Calculates performance metrics (MSE, R² Score)

🛠️ Tech Stack
	•	Python
	•	yfinance
	•	pandas, numpy
	•	matplotlib, seaborn
	•	scikit-learn

📌 Future Improvements
	•	Add LSTM for better time series forecasting
	•	Support multiple stocks
	•	Real-time prediction and web integration

📂 Dataset

Data is pulled directly from Yahoo Finance using the yfinance library.