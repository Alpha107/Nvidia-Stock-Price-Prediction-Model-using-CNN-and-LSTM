
# Nvidia Stock Price Prediction using CNN and LSTM

## Project Description

This project aims to predict Nvidia stock prices using advanced deep learning models, including Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM). Stock price prediction is a challenging task due to the complex, non-linear nature of financial markets. This project demonstrates the application of two prominent deep learning architectures to address this challenge and compares their performance in predicting future stock prices.

## Overview
The project leverages historical Nvidia stock price data and builds two models:

**- CNN Model:**  Captures spatial dependencies in stock price trends and effectively identifies patterns using convolutional layers.

**- LSTM Model:** Utilizes long-term dependencies and sequential patterns in the data to make predictions.
  
The two models are trained on historical stock price data and evaluated using common regression metrics, such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²).

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
  
## Technologies Used

- Python
- TensorFlow / Keras
- Matplotlib / Seaborn for visualization
- Pandas / NumPy for data manipulation

## Result

### Pre-Processing Results:

**- Data Preprocessing:**

![20](https://github.com/user-attachments/assets/02889127-441a-4df0-a5e5-743f7086ef90)
![21](https://github.com/user-attachments/assets/cc848bd1-0c60-45ca-bd0a-cd1f27190a3d)
![22](https://github.com/user-attachments/assets/1c04433e-53c8-4d2a-af59-2ffb6a552ee7)

### Actual vs Prediction Results:

**- LSTM:**

![output(LSTM)](https://github.com/user-attachments/assets/6f3287ac-1698-4eda-a697-d01d92e9d010)

**Calculated Matrices:**

- Mean Squared Error (MSE): 3.399395413605312
- Root Mean Squared Error (RMSE): 1.843744942665691
- Mean Absolute Error (MAE): 1.2186561350765386
- R-squared (R²): 0.9742695207142454


**- CNN:**

![output(CNN)](https://github.com/user-attachments/assets/53c45eb3-b5ed-4611-ba25-615a11a85724)

**Calculated Matrices:**

- Mean Squared Error (MSE): 1.9579597101402837
- Root Mean Squared Error (RMSE): 1.3992711353202008
- Mean Absolute Error (MAE): 1.0133344554842056
- R-squared (R²): 0.9857122381643261

## Conclusion

In this project, we implemented and compared two deep learning models, Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM), for predicting Nvidia stock prices. Both models were evaluated based on several performance metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²).

From above results we can see that the CNN model had lower MSE, RMSE, and MAE values, indicating a more accurate prediction of stock prices. Additionally, its higher R² score (0.986) suggests that the CNN model explained a larger portion of the variance in stock prices compared to the LSTM model (R² of 0.974).

**Key Insights:**

- **CNN outperforms LSTM:** CNN provided better stock price predictions by capturing both local and global features in the data, especially in time series patterns like stock prices.
- **Deep learning potential:** Both models demonstrate that deep learning techniques can effectively predict stock prices, with the CNN model performing exceptionally well in this case.
- **Future improvements:** While the CNN model yielded strong results, further improvements could be achieved by incorporating other financial indicators or experimenting with hybrid models, such as combining LSTM and CNN architectures.
