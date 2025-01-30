# Evaluating Investment Strategies: Performance, Risk, and Sharpe Ratios Over Time

This project evaluates and compares multiple investment strategies by analyzing their risk-return trade-offs, performance, and stability across different market conditions. Using Python, the project implements strategies ranging from passive index investing to elimination-based methods, providing actionable insights for diverse investor profiles.

---

## Objective

To evaluate and optimize investment strategies by analyzing key performance metrics, such as:
- **RF (Risk-Free Strategy):** Baseline returns using Treasury rates.
- **S1 (Market Index Strategy):** Buy-and-hold SPY ETF.
- **S2 (Momentum Strategy):** Return based on daily price movements.
- **S3 (Hybrid Momentum Strategy):** Combines multiple momentum indicators.
- **S4 Variants:** Eliminates extreme performers to reduce volatility:
  - **S4a**: Eliminates top/bottom 1 performer.
  - **S4b**: Eliminates top/bottom 2 performers.
  - **S4c**: Eliminates top/bottom 3 performers.

---

## Key Findings

1. **Risk-Return Trade-Offs:**
   - **S1 (Market Index):** High returns but higher volatility.
   - **S2 (Momentum):** Best during bull markets; higher drawdowns in corrections.
   - **S3 (Hybrid Momentum):** Balanced risk-return with the highest Sharpe Ratio.
   - **S4b (Moderate Elimination):** Stable performance with reduced volatility.

2. **Performance by Decade:**
   - Momentum-based strategies (S2, S3) excelled in growth periods.
   - Elimination strategies (S4 variants) offered stability in volatile markets.

3. **Real-World Challenges:**
   - **Transaction Costs:** High for frequent trading strategies.
   - **Market Liquidity:** Assumes frictionless trading, which may not hold.
   - **Tax Implications:** Active strategies face higher capital gains taxes.

---

## Tools and Techniques

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, yfinance.
- **Metrics:** Mean return, volatility, Sharpe Ratio, and cumulative returns.
- **Visualizations:** Risk vs. return scatter plots, Sharpe Ratios, and cumulative return charts.

---

## Deliverables

- **Jupyter Notebook:** Contains detailed analysis, code, and visualizations.
- **PDF Report:** A concise summary of the findings and methodology.

---

## Conclusion

**S3 (Hybrid Momentum Strategy)** is the most suitable for balanced investors, offering the highest Sharpe Ratio. For conservative investors, **S4b (Moderate Elimination Strategy)** provides stable returns with reduced risk.

---
