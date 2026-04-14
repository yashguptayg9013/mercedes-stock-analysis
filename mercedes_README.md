# 📈 Mercedes-Benz Stock Analysis

A comprehensive end-to-end financial data analysis of Mercedes-Benz (MBG.DE) stock performance using Python. This project explores historical price trends, risk metrics, moving average trading signals, and seasonal patterns to support investment decision-making.

---

## 📌 Business Question

> *How has Mercedes-Benz stock performed historically in terms of returns, risk, and predictable patterns — and what signals can inform smarter investment timing?*

---

## 📊 Analysis Coverage

| # | Analysis | Description |
|---|----------|-------------|
| 1 | **Price History** | Long-term closing price trend with key market events annotated |
| 2 | **Yearly Returns** | Annual return % comparison to identify high/low performance years |
| 3 | **Risk & Drawdown** | Volatility analysis and maximum drawdown from peak |
| 4 | **Return Distribution** | Histogram of daily returns to assess normality and tail risk |
| 5 | **MA Signals** | 50-day vs 200-day moving average crossover (Golden/Death Cross) |
| 6 | **Seasonality** | Monthly return patterns to identify seasonal performance trends |
| 7 | **Recent Performance** | Focused analysis on the last 12 months |
| 8 | **Metrics Summary** | Sharpe ratio, CAGR, max drawdown, annualised volatility |

---

## 🔍 Key Findings

- Mercedes-Benz shows **strong seasonality**, with historically better performance in Q1 and Q4
- The **200-day MA** acted as a reliable support/resistance level across multiple market cycles
- **Maximum drawdown** of ~45% observed during 2021–2022 global supply chain disruption
- Annualised volatility places it in the **mid-risk** category compared to broader European auto sector

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📁 Repository Structure

```
mercedes-stock-analysis/
│
├── Mercedes_Stock.csv                  # Historical OHLCV price data
├── Mercedes_Stock_Analysis.ipynb       # Main analysis notebook
├── fig_01_price_history.png
├── fig_02_yearly_returns.png
├── fig_03_risk_drawdown.png
├── fig_04_return_distribution.png
├── fig_05_ma_signals.png
├── fig_06_seasonality.png
├── fig_07_recent_performance.png
├── fig_08_metrics_summary.png
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yashguptayg9013/mercedes-stock-analysis.git
cd mercedes-stock-analysis

# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook Mercedes_Stock_Analysis.ipynb
```

---

## 📬 Author

**Yash Gupta** — MSc Business Analytics, Dublin Business School
[LinkedIn](https://www.linkedin.com/in/yashguptayg9013/) · [GitHub](https://github.com/yashguptayg9013)
