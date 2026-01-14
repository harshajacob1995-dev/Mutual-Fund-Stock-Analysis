📊 Mutual Fund Plan Using Python
📌 Project Overview

This project builds a data-driven mutual fund investment strategy using historical Nifty 50 closing price data. The goal is to identify stocks that provide high long-term returns with controlled risk, construct a balanced portfolio, and simulate systematic investment (SIP) returns over time.

🎯 Objectives

Analyze stock performance using ROI and volatility

Select companies with high returns and low risk

Allocate investments using inverse volatility weighting

Compare mutual fund risk with high-growth stocks

Simulate long-term wealth creation using a monthly SIP with annual step-up

🗂 Dataset

Historical closing prices of Nifty 50 companies

Data source: CSV file

Preprocessing included date conversion and missing value checks

🔍 Methodology
1. Data Preparation

Loaded stock price data

Converted date column to datetime

Verified data completeness

2. Metrics Calculation

Returns: Percentage change of prices

Volatility: Standard deviation of returns (risk measure)

ROI: Long-term return using initial and final prices

3. Stock Selection

Selected stocks with:

ROI above the median

Volatility below the median

4. Portfolio Allocation

Used inverse volatility weighting

Lower-risk stocks receive higher allocation

5. Risk Comparison

Compared mutual fund stocks with top high-growth stocks

Visualized volatility differences using bar charts

6. SIP Return Simulation

Monthly investment: ₹5,000

Annual step-up: 10%

Compounded monthly

Evaluated returns for 1, 3, 5, and 10 years

📈 Key Insights

High-growth stocks offer higher returns but come with higher risk

The mutual fund portfolio provides stable, risk-adjusted returns

Long-term SIP investments significantly benefit from compounding

🛠 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Plotly

📦 Project Output

Selected mutual fund companies

Investment allocation percentages

Risk comparison visualizations

SIP-based future value projections

🔮 Future Enhancements

Add Sharpe Ratio and risk-adjusted return metrics

Include inflation-adjusted returns

Compare SIP vs lump-sum investments

Extend analysis to other market indices

🧠 Conclusion

This project demonstrates how data analytics and financial metrics can be combined to design a risk-balanced mutual fund strategy and evaluate long-term wealth creation through systematic investing.
