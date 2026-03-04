# 🚗 Mercedes-Benz Stock Analysis (1996–2026)
### 30 Years of Financial Data | Python · Pandas · Matplotlib · Seaborn

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Finance](https://img.shields.io/badge/Domain-Finance%20%26%20Investing-0A2744)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

A comprehensive financial analysis of **Mercedes-Benz Group AG (MBG.DE)** stock using 30 years of daily trading data (1996–2026). This project demonstrates the end-to-end workflow of a financial/business analyst: data cleaning, return analysis, risk metrics, technical signals, and storytelling through visualisation.

**Dataset:** Mercedes-Benz Historical Stock Data (7,511 trading days)  
**Ticker:** MBG.DE (Frankfurt Stock Exchange)  
**Scope:** Open · High · Low · Close · Adjusted Close · Volume

---

## 🎯 Analysis Questions

1. What is the long-term price trend and total return over 30 years?
2. Which years were the best and worst performers — and why?
3. How risky is Mercedes-Benz as an investment? (Volatility, Drawdown, Sharpe, VaR)
4. What do Moving Average crossover signals tell us about trend direction?
5. Are there seasonal patterns in monthly returns and volume?
6. How has the stock performed in the recent 2020–2026 period?

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| **Total Return (1996–2026)** | +57.1% |
| **Average Annual Return** | +6.3% |
| **Best Year** | 2013 (+47.7%) |
| **Worst Year** | 2008 (-58.7%) |
| **Annual Volatility** | ~34% |
| **Max Drawdown** | -82.9% (March 2009) |
| **Sharpe Ratio** | 0.16 |
| **Win Rate** | 19 of 29 years (66%) |
| **1-Day VaR (95%)** | -2.2% |

---

## 💡 Key Insights

1. **Highly cyclical stock** — Mercedes tracks the global macro cycle closely. The 2000 dot-com crash, 2008 GFC, and 2020 COVID all produced severe drawdowns.

2. **Strong post-recession recoveries** — The 2009–2013 period delivered 5 consecutive positive years as auto demand rebounded strongly.

3. **EV transition headwinds (2022–2024)** — Underperformance in recent years reflects investor uncertainty around traditional OEMs adapting to the electric vehicle era.

4. **Low risk-adjusted returns** — A Sharpe ratio of 0.16 means the annual volatility of ~34% is not well compensated by the average +6.3% return. Buy-and-hold requires patience and conviction.

5. **Seasonality** — April and November have historically been the strongest months; September tends to be the weakest.

---

## 📁 Analysis Sections

```
1.  Setup & Data Loading           ← Feature engineering, summary stats
2.  Long-Term Price History        ← 30-year chart, MA overlay, volume
3.  Yearly Returns Analysis        ← Bar chart of annual returns with win/loss count
4.  Risk & Drawdown Analysis       ← Max drawdown, rolling volatility
5.  Return Distribution            ← Histogram, VaR, monthly heatmap (2015–2025)
6.  Moving Average Signals         ← Golden Cross / Death Cross identification
7.  Seasonality & Volume Patterns  ← Monthly return, volume, and win rate
8.  Recent Performance (2020–2026) ← Indexed price, OHLC, rolling 52w return
9.  Key Metrics Summary Table      ← All-in-one reference card
10. Executive Summary              ← Investment insights & narrative
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| `pandas` | Time-series manipulation, resampling |
| `matplotlib` | Price charts, OHLC bars, volume |
| `seaborn` | Monthly heatmaps |
| `numpy` | Volatility, return calculations |
| `scikit-learn` | (Linear regression trend, optional) |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/yourusername/mercedes-stock-analysis.git
cd mercedes-stock-analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Add the dataset to the project root (Mercedes_Stock.csv)

# Launch notebook
jupyter notebook Mercedes_Stock_Analysis.ipynb
```

---

## 📁 Project Structure

```
mercedes-stock-analysis/
│
├── Mercedes_Stock_Analysis.ipynb  # Main analysis notebook
├── README.md                       # This file
├── Mercedes_Stock.csv              # Dataset (add after cloning)
└── fig_01 to fig_08 *.png         # Pre-rendered charts
```

---

## ⚠️ Disclaimer

This project is for **educational and portfolio purposes only**. It does not constitute financial advice. Past performance is not indicative of future results.

---

*Analysis by: [Your Name] | Data: Mercedes-Benz Historical Stock | Tools: Python, Pandas, Matplotlib*
