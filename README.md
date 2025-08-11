# Stock Data Analysis and Portfolio Management Project

## Overview

This project involves analyzing stock data, calculating returns, assessing risk, and optimizing portfolios using various financial metrics and models. The project aims to provide insights into stock performance, portfolio returns, and risk management strategies.

## Data Sources

- **Yahoo Finance:** Historical stock data is retrieved using the `yfinance` library.

## Project Structure

1. **Data Collection:**
   - Import stock data for individual securities and multiple securities using Yahoo Finance.
   - Normalize and visualize stock data for comparison.

2. **Return Calculation:**
   - Calculate simple and log returns for individual securities.
   - Compute average daily and annual returns.

3. **Portfolio Management:**
   - Calculate portfolio returns and weights for different asset allocations.
   - Assess portfolio risk using standard deviation and covariance.

4. **Risk Analysis:**
   - Compare the risk of individual securities using standard deviation.
   - Analyze covariance and correlation between stocks.

5. **Regression Analysis:**
   - Perform univariate regression to analyze the relationship between variables.
   - Calculate alpha, beta, and R-squared values.

6. **Portfolio Optimization:**
   - Use Markowitz Portfolio Optimization to find the efficient frontier.
   - Simulate different asset combinations to optimize returns.

7. **Capital Asset Pricing Model (CAPM):**
   - Calculate a security's beta and expected return using CAPM.
   - Evaluate the Sharpe Ratio for risk-adjusted returns.

8. **Monte Carlo Simulations:**
   - Forecast stock prices using Monte Carlo simulations.
   - Model potential future outcomes based on historical data.

## Data Description

- `Adj Close`: Adjusted closing price of the stock.
- `Close`: Closing price of the stock.
- `High`: Highest price of the stock during the day.
- `Low`: Lowest price of the stock during the day.
- `Open`: Opening price of the stock.
- `Volume`: Trading volume of the stock.

## Usage

To run the project, execute the Python script provided. The script will load stock data, perform calculations, and generate visualizations for analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Yahoo Finance for providing the stock market data.
- Scikit-learn for machine learning tools and libraries.
- Pandas and NumPy for data manipulation and analysis.
- Matplotlib for data visualization.
