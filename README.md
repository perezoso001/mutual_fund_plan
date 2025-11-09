# 📊 Mutual Fund Plan using Python

**ME_ID:** ACTIVITY_PROJECT_DEMO_MUTUAL_FUND_PLAN_PYTHON  
**Project Title:** Analyze Nifty 50 Closing Prices to Create a Mutual Fund Plan Based on High ROI and Low Risk  

---

## 🧭 Project Overview

The **Mutual Fund Plan with Python** project focuses on developing a Python-based application that enables investors to **create, analyze, and evaluate mutual fund investment plans**.  
By combining **financial data analysis, risk assessment, and visualization**, the project helps simulate investment strategies and understand how professional mutual fund portfolios are designed for long-term stability and returns.

---

## 🎯 Objective

To design a **data-driven mutual fund investment plan** that balances **high ROI (Return on Investment)** and **low risk**, enabling investors to make informed, optimized, and diversified portfolio decisions.

---

## 🧹 1. Data Collection & Preparation

### 🔸 Data Sourcing
Historical data on various mutual funds and companies (e.g., Nifty 50) was collected. APIs such as **Yahoo Finance** or **Alpha Vantage** can be used to gather:
- Fund prices (NAV)
- Dividends and payouts
- Fund expenses (Expense Ratio)
- Historical monthly or annual returns  

### 🔸 Data Cleaning
- Checked and removed missing or inconsistent values.  
- Resampled data to ensure consistent time intervals (monthly or quarterly).  
- Converted date columns into a standard datetime format.

### 🔸 Feature Engineering
Calculated key performance metrics:
- **Total Return:** Growth of ₹1 (or $1) invested in the fund.  
- **Annualized Return:** Average yearly return over the period.  
- **Volatility (Standard Deviation):** Measure of price fluctuation and risk.  
- **Expense Ratio:** Portion of assets used for operational costs.

---

## 🧩 2. Portfolio Construction

- **Investment Weighting:** Users can allocate funds (e.g., 60% in Fund A, 40% in Fund B).  
- **Diversification Logic:** Ensures a balanced mix of assets to reduce risk.  
- **Performance Simulation:** Historical data is used to backtest performance under various market scenarios.

---

## 📈 3. Risk & Return Analysis

### Key Metrics
- **Expected Return:** Based on historical fund returns and portfolio weights.  
- **Volatility:** Quantifies investment risk.  
- **Sharpe Ratio:** Measures risk-adjusted return (higher is better).  
- **Sortino Ratio:** Focuses on downside risk (useful for loss-averse investors).

### Advanced Techniques
- **Monte Carlo Simulation:** Runs thousands of random trials to estimate future portfolio performance and visualize outcome distributions.

---

## 📊 4. Visualization & Reporting

Generated using **Matplotlib**, **Seaborn**, or interactive frameworks like **Streamlit** or **Dash**:

- **Performance Charts:** Track portfolio value over time versus benchmark indices (e.g., Nifty 50 or S&P 500).  
- **Risk-Return Scatter Plot:** Visualize trade-offs between risk and expected return.  
- **Portfolio Composition Pie Chart:** Show distribution of assets across mutual funds.  
- **Heatmaps:** Highlight fund performance during specific time periods.  
- **Interactive Dashboard:** Allow users to adjust allocations and instantly view projected outcomes.

---

## ⚙️ 5. User Interaction & Plan Generation

### Customizable Inputs
Users can define:
- Initial investment amount  
- Investment horizon (5, 10, or 20 years)  
- Risk tolerance level (Conservative / Balanced / Aggressive)

### Recommendations
- Suggests optimal mutual fund portfolios based on user preferences.  
- Recommends allocation ratios aligned with risk profiles.

### Investment Summary
Automatically generates a report including:
- Historical performance metrics  
- Risk-return indicators  
- Future performance projections under simulated conditions

---

## 🧠 6. Conclusion & Optimization

- **Optimization Algorithms:** Used **Mean-Variance Optimization** to determine ideal asset allocation that maximizes return for a given level of risk.  
- **Sensitivity Analysis:** Demonstrates how altering fund weights impacts portfolio risk and return.  
- **Long-Term Insight:** Highlights the importance of compounding and consistent investment growth.

---

## 📦 Deliverables

- Cleaned and analyzed mutual fund dataset  
- Python scripts for return, volatility, and Sharpe ratio computation  
- Visualization modules for performance and risk analysis  
- Portfolio optimization and simulation scripts  
- Summary report with insights and investment recommendations  

---

## 🧰 Tools & Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| **Programming Language** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Optimization & Simulation** | SciPy, Monte Carlo Simulation |
| **Dashboard / Interaction** | Streamlit or Dash |
| **Environment** | Jupyter Notebook / Google Colab |

---

## 📘 Summary

This project demonstrates how **Python** can be used to design and evaluate a **mutual fund investment plan** using real financial data.  
It combines **data analytics, risk modeling, portfolio theory, and visualization** to simulate how professional fund managers build investment portfolios that balance **risk and reward**.

The project ultimately provides a **foundation for long-term financial planning**, emphasizing the benefits of **data-driven decision-making** and **compound growth**.

---

## 👨‍💻 Author

**Praveen Raju P**  
Project: *Mutual Fund Plan using Python*  
