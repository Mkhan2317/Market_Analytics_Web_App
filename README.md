
# Stock Data Analysis App

## Overview

This project is a Streamlit web application for analyzing stock data using technical analysis indicators. It allows users to select a stock ticker, specify a date range, and apply various technical indicators to visualize the stock's performance. The app retrieves data from Yahoo Finance and computes indicators like Simple Moving Average (SMA), Exponential Moving Average (EMA), and Relative Strength Index (RSI) using the TA-Lib library.

## Features

- **Download Stock Data**: Fetch historical stock data for a given ticker symbol and date range.
- **Technical Indicators**: Apply and visualize key technical indicators:
  - **Simple Moving Average (SMA)**
  - **Exponential Moving Average (EMA)**
  - **Relative Strength Index (RSI)**
- **Interactive Interface**: Use Streamlit's interactive widgets to select tickers, date ranges, and indicators.



## Requirements

- Python 3.x
- Streamlit
- Pandas
- TA-Lib
- yfinance
