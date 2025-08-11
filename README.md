# Stock Data Analysis and Portfolio Management Project

## Overview

This project involves analyzing stock data, calculating returns, assessing risk, and optimizing portfolios using various financial metrics and models. The project aims to provide insights into stock performance, portfolio returns, and risk management strategies.

## Data Sources

- **Yahoo Finance:** Historical stock data is retrieved using the `yfinance` library.
- **Pandas DataReader:** Used to pull data from various APIs like Alpha Vantage, IEX Cloud, or Quandl.

## Libraries Used
- Scikit-learn for machine learning tools and libraries.
- Pandas and NumPy for data manipulation and analysis.
- Statsmodels and SciPy for statistical analysis.
- Matplotlib for data visualization.

## Project Structure

1. **Data Collection:**
   - Import stock data for individual securities and multiple securities using `yfinance` and `pandas_datareader`.

2. **Data Processing:**
   - Clean and process the dataset to include relevant features for analysis.
   - Calculate simple and log returns for individual securities.
   - Normalize stock data to a base value for comparison.

3. **Portfolio Management:**
   - Calculate portfolio returns and weights for different asset allocations.
   - Assess portfolio risk using standard deviation and covariance.
   - Calculate portfolio variance and volatility.

4. **Risk Analysis:**
   - Calculate individual security risk using standard deviation.
   - Compute covariance and correlation matrices to analyze relationships between stocks.
   - Assess diversifiable and non-diversifiable risk of a portfolio.

5. **Regression Analysis:**
   - Perform univariate regression to analyze the relationship between features.
   - Calculate covariance and correlation matrices to understand relationships between stocks.

6. **Monte Carlo Simulations:**
   - Use past data to create simulations and observe different possible realizations of stock prices.
   - Forecast future stock prices using Brownian motion and other statistical methods.

7. **Derivative Contracts:**
   - Understand and calculate the value of derivative contracts such as call options using the Black-Scholes-Merton model.
   - Analyze the call option's payoff based on strike price and share price.

## Data Sources

- **S&P 500 Index Data:** Historical data for the S&P 500 index is retrieved using the `yfinance` library.
- **Additional Stock Data:** Data for other selected stocks is also retrieved using `yfinance` and `pandas_datareader`.

## Project Results

### Stock Analysis Results
- **S&P 500 Data:** Historical data for the S&P 500 index was successfully imported and analyzed.
- **Simple and Log Returns:** Calculated for individual securities to assess daily and annual returns.
- **Portfolio Management:** Portfolio returns and risk metrics were calculated using equal weighting and different asset allocations.
- **Risk Analysis:** Systematic and diversifiable risks were calculated for the portfolio.
- **Regression Analysis:** Univariate regression was performed to analyze relationships between features.
- **Monte Carlo Simulations:** Simulations were conducted to observe different possible realizations of events.

## Usage

To run the project, execute the Jupyter Notebook provided. The notebook will load stock data, perform calculations, and generate visualizations for analysis and model predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Yahoo Finance for providing the stock market data.
# Calculate portfolio volatility (standard deviation)
pf_vol = pf_var ** 0.5
print(str(round(pf_vol, 5) * 100) + "%")
