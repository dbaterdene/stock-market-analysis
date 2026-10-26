# Stock Market Analysis: Apple, Microsoft & NVIDIA

## Project Overview

This project analyzes historical stock prices and company financial information for Apple (AAPL), Microsoft (MSFT), and NVIDIA (NVDA) using Python.

The goal is to demonstrate practical data analyst skills, including data cleaning, exploratory analysis, financial metric calculation, data visualization, and dashboard development.

## Business Questions

- How did the three stocks perform over the selected historical period?
- Which stock experienced greater return volatility and deeper drawdowns?
- How did their short-term and long-term price trends compare?
- How do revenue growth, net income, profit margin, and valuation metrics differ?
- How can multiple financial indicators be combined into a clear comparison?

## Tools and Technologies

- **Python** — analysis and automation
- **pandas and NumPy** — data cleaning and calculations
- **Matplotlib** — static charts
- **Plotly** — interactive visualizations and dashboard
- **yfinance** — retrieval of historical market and company financial data
- **Git and GitHub** — version control and project documentation

## Project Workflow

1. **Data collection:** Retrieve historical prices for AAPL, MSFT, and NVDA.
2. **Data cleaning:** Validate dates, prices, missing values, and duplicate records.
3. **Return analysis:** Calculate daily returns, cumulative returns, total returns, and compound annual growth rates (CAGR).
4. **Risk analysis:** Calculate annualized volatility and maximum drawdown.
5. **Trend analysis:** Calculate 20-day, 50-day, and 200-day moving averages.
6. **Fundamental analysis:** Examine revenue, net income, profit margin, debt, cash, and valuation metrics where available.
7. **Comparative analysis:** Combine the results into a consolidated stock comparison report.
8. **Dashboard development:** Present the analysis through interactive charts and summary metrics.

## Repository Structure

```text
stock-market-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── figures/
├── reports/
├── src/
├── requirements.txt
├── .gitignore
└── README.md
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd stock-market-analysis
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of your repository.

### 2. Create and activate a virtual environment

On macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the analysis scripts

Run the scripts in the order below:

```bash
python src/download_stock_data.py
python src/clean_stock_data.py
python src/analyze_returns.py
python src/analyze_risk.py
python src/calculate_moving_averages.py
python src/analyze_fundamentals.py
python src/compare_stocks.py
python src/create_dashboard.py
```

The scripts generate analysis reports and visualizations in the `reports/` and `figures/` directories.

## Key Outputs

- Historical stock price comparison
- Investment growth comparison
- Annualized volatility and maximum drawdown analysis
- Moving-average charts
- Fundamental financial summary
- Consolidated stock comparison report
- Interactive HTML dashboard

**Dashboard:** After running the project, open `reports/stock_market_dashboard.html` in a web browser.

## Findings

The analysis is designed to compare historical performance, risk, price trends, and company fundamentals across the three stocks.

Specific findings should be reported only after reviewing the generated outputs. Historical results do not guarantee future performance.

## Data Sources and Limitations

Market prices and company financial information are retrieved using `yfinance`, which provides access to Yahoo Finance data. Data availability and reporting periods can vary by company and metric.

This project is for educational and analytical purposes. It is not investment advice. The analysis does not account for every real-world investment factor, such as taxes, transaction costs, or future market uncertainty.

## Skills Demonstrated

- Data acquisition and validation
- Data cleaning and transformation
- Financial and statistical analysis
- Python scripting and automation
- Data visualization and dashboard development
- Reproducible analytical workflows
- Technical documentation and version control

---

**Author:** Your Name  
**Role Focus:** Data Analyst  
**Project:** Stock Market Analysis Portfolio