# Stock Market Analysis

This project performs a comprehensive analysis of stock market data for a selected list of Indian companies (RELIANCE.NS, TCS.NS, INFY.NS, HDFCBANK.NS) over the past year. The analysis includes:

## Data Acquisition and Preparation

- Historical stock data is downloaded using the yfinance library.
- The data is cleaned, preprocessed, and pivoted for further analysis.

## Exploratory Data Analysis

- Visualizations are created to understand the trends in Adjusted Closing Prices over time.
- Moving averages (50-day and 200-day) are calculated and plotted to identify potential buy/sell signals.
- The distribution of daily returns is visualized using histograms and kernel density plots.
- A correlation matrix is generated to understand the relationships between the stocks.

## Portfolio Optimization

- Expected returns and volatility are calculated for each stock.
- The Efficient Frontier is generated using Monte Carlo simulations to visualize the optimal portfolios.
- The portfolio with the maximum Sharpe Ratio is identified and its composition is presented.

## Libraries Used

- pandas
- yfinance
- matplotlib
- seaborn
- numpy

## How to Use

1. Install the required libraries:
   2. Run the provided Python code in a Google Colab environment.

## Disclaimer

This project is for educational and informational purposes only and should not be considered as financial advice.
