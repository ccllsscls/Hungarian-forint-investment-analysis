# Tableau: Hungarian forint investment analysis (2019 - 2026)
In high-inflation environments, investors often believe that converting local currency into euros will protect their wealth.

But does currency timing actually work?

This project analyzes investment strategies in Hungary between 2019 and 2026 using an interactive Tableau dashboard. By combining inflation data, EUR/HUF exchange rates, and simulated investment returns, the model compares nominal asset growth with real purchasing power.

The analysis reveals a counter-intuitive result: despite significant currency volatility, FX timing generates very limited gains, while passive HUF bond investments deliver higher long-term value.

---

# Dashboard

Interactive Tableau dashboard:
https://public.tableau.com/app/profile/alice.cls/viz/HUFInvestmentAnalysis/YearMonthView?publish=yes

Key finding: currency timing generated less than €300 over five years and **significantly underperformed a passive 5% bond strategy**.

---

# Key Questions

1. How does investment allocation influence long-term wealth growth?
2. Can FX timing strategies outperform passive investments?
3. How do inflation and exchange rate movements affect real wealth?

---

# Project Structure

The project consists of three analytical Tableau dashboards:

## 1. Investment Strategy Simulator

An interactive dashboard that allows users to adjust:

- Investment allocation ratio
- Annual return assumptions for two investment products

It compares: Nominal Wealth vs Real Wealth (inflation adjusted)

Key insight:
1. Nominal wealth appears to grow steadily, but once inflation and currency depreciation are considered, real purchasing power grows much slower.
2. The effect is especially visible during the **2022–2024 inflation spike**.


## 2. FX Timing Strategy

This dashboard tests a rule-based currency exchange strategy using a **3-month rolling average of the EUR/HUF exchange rate**.

FX conversion is triggered when the current exchange rate is more favorable than the recent average.

Key finding:
1. FX timing opportunities are rare.
2. Between 2020 and 2024, the strategy generates less than **€300 of additional value**, significantly underperforming a simple **5% bond investment strategy**.


## 3. Macroeconomic Drivers

This dashboard visualizes yearly and monthly trends in:

- Inflation
- EUR/HUF exchange rate

Key insight:
1. Exchange rates and inflation do not move together consistently.  
2. Year **2022** represents the most severe macroeconomic shock, with both high inflation and strong HUF depreciation.

---

# Tools Used

- Tableau (Data Visualization)
- Excel (Data preparation)
- Financial modeling
- Time series analysis

Key Tableau techniques include:

- Table Calculations
- Moving averages
- Running totals
- Parameter-driven simulations
- Interactive dashboards

---

# Data Sources

The dataset includes monthly observations from **June 2019 to February 2026** and contains:

- Exchange rate (EUR/HUF)
- Inflation rate
- Monthly income and savings
- Simulated investment returns

Some financial metrics were pre-calculated outside Tableau to overcome calculation layer limitations.

---

# Documentation

The documentation includes:
- Model design decisions
- Calculation logic
- Tableau limitations and workarounds
- Key insights and limitations

---

# Key Takeaway

The project demonstrates that **nominal asset growth can be misleading**.  
When inflation and currency depreciation are considered, real wealth growth can be significantly lower than expected.
