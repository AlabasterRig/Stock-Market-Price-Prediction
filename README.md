# Stock Market Price Prediction

This project predicts stock prices for Google (GOOG), Apple (AAPL), and Amazon (AMZN) using historical stock market data. The data is obtained from Yahoo Finance and analyzed using various visualizations and regression techniques to model the stock price trends.

## Project Overview

- **Programming Languages:** Python
- **Libraries Used:** 
  - `pandas`, `numpy`, `matplotlib`, `seaborn` (for data manipulation and visualization)
  - `yfinance` (for downloading stock market data)
  - `scikit-learn` (for machine learning models and evaluation metrics)
- **Stocks Analyzed:** 
  - Google (GOOG)
  - Apple (AAPL)
  - Amazon (AMZN)
- **Period:** 2019-2020 for historical analysis and 2023-2024 for predictions

## Project Features

### Data Collection
- Historical data for GOOG, AAPL, and AMZN is fetched using `yfinance` from January 2019 to December 2020.
- Additional data from January 2023 to February 2024 is fetched for stock price prediction.

### Visualizations
- **Closing Price:** A time series plot showing the daily closing prices for each stock.
- **Sales Volume:** Visualizes the volume of sales for each company over time.
- **Daily Returns:** A histogram of daily percentage returns for each stock.
- **Correlation Heatmaps:** Correlation between stock returns and closing prices across companies.

### Prediction Models
- **Random Forest Regressor** is used to predict stock prices for Apple, Google, and Amazon.
- The models are evaluated using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared (R2)
  
## Results
- The project compares the performance of Random Forest models for each stock in terms of Training MSE % and Testing MSE %.
- Results are presented in tabular format for better comparison.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-market-prediction.git
   cd stock-market-prediction

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   
3. Run the project:
   ```bash
   python stock_prediction.py

## Usage
- Visualizations of stock trends can help investors analyze the historical behavior of stocks.
- Predictive models can assist in making informed decisions about future investments.
