# Stock Financial Time Series Analysis
Concise notebook-driven exploration of stock market data using Yahoo Finance. It covers basic price analysis, returns, CAPM, and portfolio concepts.

## Quick start
- Open the notebook: `Stock Analysis Project.ipynb`.
- Run the cells top to bottom in Jupyter, VS Code, or Google Colab.

## Play with different stocks
Search for the `ticker` or `tickers` variables in the notebook and replace the symbols with your own. Common spots include:
- `ticker = 'NVDA'` for single-stock examples
- `tickers = ['TSLA', 'MSFT', 'GS', '^GSPC']` for multi-stock and market comparisons

Tip: `^GSPC` is the S&P 500 index. Keep it if a cell compares stocks vs. the market.

## Requirements
- Python 3.x
- Libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`, `statsmodels`, `scikit-learn`

Install example:
```bash
pip install yfinance pandas numpy matplotlib statsmodels scikit-learn
```
