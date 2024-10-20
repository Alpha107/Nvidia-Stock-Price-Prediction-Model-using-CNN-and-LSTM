
# Nvidia Stock Price Prediction using LSTM

## Project Description

This project focuses on analyzing Nvidia stock prices to forecast future trends and provide financial insights. Leveraging time-series forecasting and clustering techniques, the analysis explores historical data to predict future stock price movements and helps suggest potential saving goals based on market trends. The model is designed to aid investors in making data-driven decisions by predicting stock price trajectories and categorizing stock behavior.

## Dataset Information

The dataset used in this project consists of historical Nvidia stock prices, which include the following parameters:

- **Date**: The trading day.
- **Open**: Opening price of the stock.
- **High**: The highest price reached within the trading session.
- **Low**: The lowest price within the session.
- **Close**: The closing price of the stock at the end of the session.
- **Adj Close**: Adjusted closing price accounting for corporate actions.
- **Volume**: Number of shares traded on that day.

This dataset serves as the foundation for the time-series analysis and forecasting. It contains vital information for predicting future stock trends, understanding price patterns, and determining market behavior.

## Key Features of the Project

1. **Time-Series Forecasting**:
   - Utilizes advanced forecasting techniques like ARIMA, LSTM, or Prophet to predict future Nvidia stock prices based on past data.
   - Helps investors anticipate future stock movements for decision-making.

2. **Clustering of Stock Behavior**:
   - Clustering techniques are applied to group different time periods based on stock price patterns.
   - This enables the identification of periods with similar market behavior, assisting in understanding stock volatility and long-term trends.

3. **Data-Driven Financial Insights**:
   - Predicts future stock prices and provides suggestions on optimal saving goals based on market movements.
   - Helps investors optimize financial planning by leveraging stock price predictions.

## Objectives

The goals of this project are:

- **To analyze Nvidia’s stock price history**: Conduct in-depth analysis of trends, fluctuations, and overall behavior of the stock.
- **To forecast future prices**: Provide accurate predictions of future stock prices using time-series modeling.
- **To categorize stock price trends**: Identify distinct trends and behavior patterns using clustering techniques.
- **To aid financial decision-making**: Offer valuable insights that could influence saving strategies and investments based on stock price predictions.

## Project Workflow

1. **Data Preprocessing**:
   - Load and clean the Nvidia stock price dataset.
   - Handle missing data, remove outliers, and prepare the dataset for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize historical trends in Nvidia stock prices.
   - Create time-series plots to observe the fluctuations in stock price over the years.
   - Plot volume traded, high/low price fluctuations, and moving averages.

3. **Time-Series Forecasting**:
   - Implement forecasting models to predict future stock prices.
   - Analyze the model performance and optimize it for better accuracy.

4. **Clustering Analysis**:
   - Apply clustering algorithms to group similar time periods.
   - Visualize stock price behavior in different clusters and interpret the results.

## Result

![output](https://github.com/user-attachments/assets/9e8dea39-9b5c-421d-b2cd-d40c3cfd42f2)

## Calculated Matrices:

- **Mean Squared Error (MSE):** 3.399395413605312
- **Root Mean Squared Error (RMSE):** 1.843744942665691
- **Mean Absolute Error (MAE):** 1.2186561350765386
- **R-squared (R²):** 0.9742695207142454

## Conclusion

This project leverages historical data and machine learning models to forecast Nvidia stock prices and suggest future market behaviors. The insights provided by this analysis can help investors with financial decision-making and allow for better planning of future investments and saving strategies. By understanding the stock’s historical patterns, we can make informed predictions about future stock prices and market movements.
