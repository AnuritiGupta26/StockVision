# StockVision : Stock Price Prediction Model with KNN
StockVision is an AI-powered stock price prediction model that leverages machine learning algorithms to forecast the future performance of stocks. The project utilizes historical market data, including stock prices, volumes, and other market indicators, to predict price trends and provide valuable insights for investors.

This project showcases how KNN algorithms can be used to handle both regression (predicting continuous stock prices) and classification (predicting whether a stock's price will go up or down) tasks. The model helps users understand the direction of stock price movements and provides actionable insights for investment decisions.

#### **Key Features:**
- **Data Collection:** Fetches historical stock data using financial APIs like Yahoo Finance or Quandl.
- **KNN Classification:** Predicts whether a stock price will increase or decrease (up or down classification) based on historical data.
- **KNN Regression:** Provides continuous stock price predictions, estimating future stock prices based on previous trends.
- **Visualization:** Uses Matplotlib or Plotly to visualize predicted stock prices and trends, making it easier to interpret results.
- **Evaluation Metrics:** Measures model performance using metrics like accuracy, precision, recall for classification, Root Mean Sqaure for regression.

#### **How It Works:**
1. **Data Collection:** The model collects historical stock data (open, close, high, low prices) and other indicators.
2. **Data Preprocessing:** The data is cleaned and preprocessed, handling missing values and normalizing features.
3. **Feature Engineering:** Important features such as moving averages and relative strength index (RSI) are derived to improve model performance.
4. **KNN Classification:** The KNN classification model is trained to predict whether the stock price will increase or decrease.
5. **KNN Regression:** The KNN regression model is used to predict the actual future stock prices.
6. **Model Evaluation:** Both models are evaluated with appropriate metrics to measure their accuracy and reliability.
7. **Visualization:** The predictions are visualized using graphs, allowing users to track predicted price trends and classifications.

#### **Technologies Used:**
- **Languages:** Python
- **Libraries:** pandas, NumPy, Scikit-learn, Matplotlib, Plotly
- **APIs:** Yahoo Finance, Quandl, Alpha Vantage
- **Modeling Techniques:** KNN Classification and Regression

#### **Goal:**
The objective of **StockVision** is to empower investors and traders to make data-driven decisions by predicting future stock price movements using the power of KNN algorithms. Whether predicting stock price directions or actual price values, the model serves as a valuable tool in navigating the stock market.

.
