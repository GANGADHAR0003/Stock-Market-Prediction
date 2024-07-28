# Stock-Market-Prediction


This project implements a simple stock market prediction and trading strategy using rolling max/min signals.

## Overview

The script analyzes historical stock price data (in this case for Google stock) and generates buy/sell signals based on rolling maximum and minimum price levels. It then simulates trading based on these signals and calculates the total gains and return on investment.

## Key Features

- Loads and processes historical stock price data
- Generates buy/sell signals using rolling max/min strategy  
- Simulates trading based on generated signals
- Calculates and visualizes trading performance

## Requirements

- Python 3.x
- pandas
- numpy  
- matplotlib
- seaborn

## Usage

1. Ensure you have the required libraries installed
2. Place the historical stock data CSV file (e.g. 'GOOG-year.csv') in the same directory
3. Run the script:
4. The script will output trading actions and final performance metrics
5. A plot will be generated showing the stock price, buy signals, and sell signals

## Customization

You can modify the following parameters in the script:

- `initial_money`: Starting capital for trading simulation
- `max_buy`: Maximum number of shares to buy in a single transaction  
- `max_sell`: Maximum number of shares to sell in a single transaction
- Rolling window size for generating signals (default is 10% of data points)

## Results

The script outputs:
- Total gains from the trading strategy
- Percentage return on investment
- A plot visualizing the stock price movement and buy/sell signals

## Disclaimer

This project is for educational purposes only. It is not financial advice and should not be used for actual trading without thorough testing and risk assessment.

## License

[MIT License](LICENSE)
![image](https://github.com/user-attachments/assets/ded59882-43d6-4977-b232-098919755570)
