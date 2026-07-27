# Stock Analysis Project

A Python-based stock market analysis notebook that uses historical data to compare the performance of **Apple (AAPL)**, **Microsoft (MSFT)**, and **Tesla (TSLA)** between **2022-01-01** and **2024-01-01**.

The project downloads stock data using `yfinance`, performs basic financial analysis, and visualizes price trends, daily returns, volatility, and correlations.

---

## Features

- Download historical stock data from Yahoo Finance
- Analyze closing prices of multiple stocks
- Plot individual stock price trends
- Compare stock prices on one chart
- Calculate daily returns
- Measure volatility
- Compute annualized volatility
- Generate correlation matrix between stocks
- Visualize correlations using a heatmap
- Calculate total return for each stock
- Summarize key metrics in a table

---

## Stocks Analyzed

- **AAPL** — Apple Inc.
- **MSFT** — Microsoft Corporation
- **TSLA** — Tesla, Inc.

---

## Project Workflow

1. Import required libraries
2. Download stock data using `yfinance`
3. Extract closing prices
4. Visualize stock price trends
5. Compute daily percentage returns
6. Calculate volatility and annualized volatility
7. Build a correlation matrix
8. Plot correlation heatmap
9. Calculate total return
10. Create a summary table

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- yFinance

---

## Installation

Install the required libraries before running the notebook:

```bash
pip install yfinance pandas matplotlib seaborn
```

---

## Usage

1. Clone this repository:

```bash
git clone https://github.com/alijalayian/Stock-Market-Analysis-with-Python.git
cd Stock-Market-Analysis-with-Python
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook
```

3. Run the notebook step by step.

---

## Example Analysis

### Closing Price Trends
The notebook plots the price movement of AAPL, MSFT, and TSLA over the selected time period.

### Daily Returns
Daily percentage change is used to observe short-term stock movement.
![Price Comparison](images/price_comparison.png)
### Volatility
The project calculates both:
- **Daily volatility**
- **Annualized volatility**

### Correlation Matrix
A heatmap is generated to show how strongly the stocks move together.
![Correlation Heatmap](images/correlation_heatmap.png)
### Total Return
The total return for each stock is calculated as:

Total Return (%) = ((Final Price / Initial Price) - 1) × 100
---

## Output Summary

The final output includes:
- Closing price charts
- Daily return statistics
- Volatility values
- Correlation matrix
- Heatmap visualization
- Total return summary table

---

## File Structure

```bash
project-1-stock-analysis.ipynb
README.md
```

---

## Possible Improvements

You can extend this project by adding:

- Moving averages
- Risk-adjusted return metrics
- Sharpe ratio
- Candlestick charts
- Portfolio simulation
- More stocks and sectors
- Interactive dashboard using Plotly or Streamlit

---

## Author

**Ali**
[GitHub](https://github.com/alijalayian)
---

## License

This project is for educational purposes.
