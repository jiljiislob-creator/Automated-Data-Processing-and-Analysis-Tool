# Automated Data Processing and Analysis Tool for Stock Market

## Project Overview
This repository contains an Automated Data Processing and Analysis Tool developed in Python, designed to handle and analyze stock market data. The tool leverages advanced data science techniques, including machine learning and technical analysis, to provide insights into stock market trends and potential investment opportunities.

## Features
- **Data Ingestion**: Utilizes `yfinance` to fetch real-time and historical stock data.
- **Technical Analysis**: Implements technical indicators like RSI, MACD, and Bollinger Bands using the `ta` library.
- **Predictive Modeling**: Employs a Random Forest Regressor to predict future stock prices.
- **Automated Alerts**: Includes a simple alert system for significant day-to-day price changes.
- **Interactive Visualization**: Uses `Plotly` for dynamic and interactive data visualization.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn
- yfinance
- TA (Technical Analysis library)
- Plotly

## Getting Started
To run this tool, you will need Python installed on your system. Clone this repository and install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn yfinance plotly ta
