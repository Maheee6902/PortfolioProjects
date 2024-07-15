# Stock Analysis of Top 50 Companies in India📈📉

This repository contains the script for analyzing the stock performance of the top 50 companies listed on the National Stock Exchange (NSE) of India. The script fetches historical stock data, calculates technical indicators, and visualizes the results using plots.

## Features

- **Top 50 Companies List:** Includes the NSE ticker symbols for the top 50 companies in India.
- **User Selection:** Prompts the user to select a company by entering its index.
- **Data Retrieval:** Fetches historical stock data from Yahoo Finance for the selected company.
- **Technical Indicators:** Calculates key technical indicators:
  - **20-day and 50-day Moving Averages (MA):** Helps identify trends and potential support or resistance levels.
  - **14-day Relative Strength Index (RSI):** Indicates overbought or oversold conditions, providing potential buy or sell signals.
- **Data Visualization:** Plots the stock's close price with the MAs and the RSI for better visual analysis.

## Tools and Databases Used🛠️

- **Yahoo Finance (yfinance):** A Python library to fetch historical market data from Yahoo Finance.
- **Pandas:** A powerful data manipulation and analysis library for Python.
- **Matplotlib:** A plotting library for creating static, animated, and interactive visualizations in Python.
- **TA-Lib (ta):** A Python library for technical analysis, which includes indicators such as moving averages and RSI.

# Inferences from the Plots

## Stock Price with Moving Averages

- **Trend Identification:** The close price plotted with the 20-day and 50-day moving averages helps identify trends.
- **Support and Resistance Levels:** The MAs can indicate potential support or resistance levels.
- **Buy/Sell Signals:** Crossovers between the MAs can signal potential buy or sell opportunities.

## Relative Strength Index (RSI)

- **Overbought/Oversold Conditions:** The RSI indicates overbought (above 70) or oversold (below 30) conditions.
- **Trading Signals:** These levels can provide potential signals for buying or selling the stock.

## Conclusion

This script provides a comprehensive analysis of the top 50 companies in India by fetching historical data, calculating important technical indicators, and visualizing them. The Moving Averages and RSI can help traders and investors make informed decisions by identifying trends, support and resistance levels, and potential buy or sell signals.
