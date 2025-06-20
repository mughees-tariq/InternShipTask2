📈 Predicting Future Stock Prices

🧠 Task Objective
The primary goal of this project is to build a predictive model that forecasts the next day's closing stock price using historical financial data. This involves:
Collecting historical stock data
Engineering features for prediction
Training a regression model
Evaluating its performance

📁 Dataset Used
Source: Yahoo Finance
Ticker: 005930.KS (Samsung Electronics Co., Ltd.)
Period: January 1, 2020 – December 31, 2024
Features: Open, High, Low, Volume (used to predict the next day's Close price)

🤖 Models Applied
Linear Regression from scikit-learn was used to model the relationship between daily stock metrics and the next day's closing price.
Data was split into training and testing sets with an 80/20 ratio, using time series order (no shuffle).

📌 Key Results and Findings
The model was trained successfully and evaluated using Mean Squared Error (MSE).
Visual inspection showed that predictions followed the general trend of actual prices but may lack precision in volatile movements.
Linear regression provided a simple baseline; performance may improve using more advanced models like LSTM, XGBoost, or ARIMA.
