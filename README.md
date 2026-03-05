# DHC-ML-Task_2
This project demonstrates Apple (AAPL) stock price prediction using a Linear Regression model trained on historical yfinance data."
```markdown
# Stock Price Prediction with Linear Regression

## Task Objective

The primary objective of this project was to predict the next day's closing price of Apple (AAPL) stock using historical stock data. The goal was to build a model that can forecast future stock prices with reasonable accuracy.

## Dataset Used

The dataset used for this project is historical stock data for Apple (AAPL), retrieved using the `yfinance` library. The data spans from January 1, 2022, to January 1, 2024. It includes features such as 'Open', 'High', 'Low', 'Close', and 'Volume'. The 'Next_Close' column, representing the closing price of the next day, was created as the target variable.

## Models Applied

**Linear Regression:** A simple yet effective supervised learning algorithm was chosen for this prediction task. The model was trained on 80% of the historical data and evaluated on the remaining 20%.

## Key Results and Findings

After training and evaluating the Linear Regression model, the following key metrics and observations were noted:

*   **Mean Absolute Error (MAE):** Approximately 1.87
*   **R2 Score:** Approximately 0.918

The R2 Score indicates that the model explains about 91.8% of the variance in the next day's closing price, which suggests a strong fit. The Mean Absolute Error of 1.87 implies that, on average, the model's predictions were off by about $1.87 from the actual closing price.

The plot of actual vs. predicted closing prices visually confirmed that the Linear Regression model performed well in capturing the trends and patterns in the stock prices, aligning closely with the actual values in the test set.

(A Random Forest Regressor was also considered, but Linear Regression performed better in terms of evaluation metrics.)
```
