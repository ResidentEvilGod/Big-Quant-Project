# Big Quant Project

A Python-based quantitative finance project exploring algorithmic trading strategies, options pricing, portfolio risk management, and market making.

This project demonstrates fundamental quantitative finance concepts through five models, using synthetic market data, statistical analysis, and performance visualizations.

## Project Features

The project includes five quantitative finance models:

1. **Momentum Backtest** — Tests a trend-following trading strategy using historical price movements, transaction costs, and out-of-sample evaluation.
2. **Options Pricing Model** — Calculates European option prices using Black-Scholes, Greeks, implied volatility, and Monte Carlo simulations.
3. **Volatility Targeting Model** — Dynamically adjusts portfolio exposure based on estimated market volatility.
4. **Pairs Trading Strategy** — Explores statistical arbitrage using rolling hedge ratios, z-scores, and mean-reversion signals.
5. **Market Making Simulator** — Simulates bid/ask pricing, order executions, inventory management, and trading profitability.

The project also includes risk metrics such as the Sharpe ratio, Sortino ratio, annualized volatility, and maximum drawdown.

## Requirements

- Python 3.10 or newer
- NumPy
- pandas
- SciPy
- Matplotlib
- Jupyter Notebook (recommended)

## Installation

**1. Clone the repository:**

```bash
git clone https://github.com/YOUR_USERNAME/quant-interview-lab.git
cd quant-interview-lab
```

Replace `YOUR_USERNAME` with your GitHub username.

**2. Install dependencies:**

```bash
python -m pip install numpy pandas scipy matplotlib jupyter
```

**3. Open the project:**

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `Big Quant Project.ipynb` and run the notebook's cells.

## How to Use

The notebook runs all five models using reproducible synthetic financial data. No API keys or external market data downloads are required.

Before running, locate the `OUTPUT_DIR` variable near the beginning of the code and change it to a directory on your computer.

```python
from pathlib import Path

OUTPUT_DIR = Path("results")
```

Running the full notebook will:

- Execute all five quantitative models.
- Calculate strategy performance and risk metrics.
- Generate six financial charts.
- Save a `report.json` file containing the simulation results.

Users can experiment by modifying strategy parameters, such as momentum lookback periods, volatility targets, trading thresholds, and market-making inventory limits.

## Technologies Used

**Python | NumPy | pandas | SciPy | Matplotlib | Jupyter Notebook**

## Disclaimer

This project is intended for educational purposes and quantitative finance research. It uses synthetic market data and simplified execution assumptions. Results do not represent verified real-world trading performance and should not be considered financial advice.
