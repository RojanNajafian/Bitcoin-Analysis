# Bitcoin-Analysis
# Bitcoin buy and sell analysis at certain time
# Bitcoin (BTC) Profit & Loss Analysis  
## Buy on Sunday (Open) – Sell on Wednesday (Close)

## Project Description
This project analyzes a very simple trading strategy for **Bitcoin (BTC)**:

- **Buy** Bitcoin every **Sunday** at the **Open** price  
- **Sell** Bitcoin every **Wednesday** at the **Close** price  
- The strategy is applied to historical data to calculate:
  - Weekly profit or loss
  - Total profit
  - Capital growth over time

The goal of this project is **educational**, focusing on basic data analysis and backtesting concepts.

---

## Data Source
- Historical BTC price data (`BTC-USD`) from **Yahoo Finance**
- Time range: **2018-01-01 to 2024-12-31**
- Data includes: Date, Open, High, Low, Close, Volume

---

## Strategy Logic
1. Extract **Sunday Open prices** (buy prices)
2. Extract **Wednesday Close prices** (sell prices)
3. Calculate weekly profit
4. Calculate total profit by summing all weekly profits
5. Plot capital growth over time
