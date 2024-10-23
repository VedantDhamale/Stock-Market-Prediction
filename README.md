
# Stock Market Prediction

This project focuses on predicting stock prices using historical stock market data from the **NIFTY-50** index, specifically from the period **2000 to 2021**. The data has been sourced from Kaggle and contains day-level pricing and trading values for the fifty stocks in the index.

## Project Overview

The goal of this project is to analyze and predict stock prices based on historical data using various machine learning and deep learning techniques. The dataset spans over two decades of trading data, making it rich in information for analysis.

### Dataset
The dataset used is from Kaggle: [NIFTY-50 Stock Market Data (2000 - 2021)](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data). It contains pricing information for 50 stocks listed on the **National Stock Exchange (NSE)** India. The data includes:

- **Date**: Trade date
- **Symbol**: Name of stock
- **Series**: Type of security
- **Prev Close**: Previous closing price
- **Open**: Opening price of the day
- **High**: Highest price during the day
- **Low**: Lowest price during the day
- **Close**: Closing price of the day
- **VWAP**: Volume-weighted average price
- **Volume**: Volume traded during the day
- **Turnover**: Turnover ratio
- **Trades**: Number of trades
- **Deliverable Volume**: Amount of deliverable volume
- **% Deliverable**: Percentage of shares delivered

### Preprocessing
- The dataset contains NaN values, particularly where 0 indicates no trade. 
- The columns with missing values include **Trades**, **Deliverable Volume**, and **% Deliverable**, which were handled by filling with 0.

## Installation & Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/VedantDhamale/Stock-Market-Prediction.git
    cd Stock-Market-Prediction
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook to explore the data and models:
    ```bash
    jupyter notebook Stock_Price_Prediction.ipynb
    ```

## Features
- **Data Preprocessing**: Handling missing values and preparing the data for model training.
- **Exploratory Data Analysis (EDA)**: Analyzing trends, patterns, and relationships in the stock data.
- **Modeling**: Implementing various machine learning and deep learning models for stock price prediction.
- **Performance Evaluation**: Assessing model performance using metrics like MSE, RMSE, and accuracy.

## Usage
The notebook provides a step-by-step process to:
- Load and preprocess the stock market data.
- Perform exploratory data analysis.
- Train predictive models.
- Visualize the results.

## Contributing
Feel free to contribute to the project by submitting a pull request or reporting issues.

## License
This project is licensed under the MIT License.

## Contact
For any queries or suggestions, feel free to reach out at:
- **GitHub**: [Vedant Dhamale](https://github.com/VedantDhamale)

---

### Add the remote repository:
```bash
git remote add origin https://github.com/VedantDhamale/Stock-Market-Prediction.git
```
