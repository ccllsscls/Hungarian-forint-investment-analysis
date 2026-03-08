# Hungarian-forint-investment-analysis

# Real vs Nominal Wealth Analysis (Hungary 2019–2026)

This project analyzes how inflation and exchange rate fluctuations affect the real value of personal wealth for Hungarian investors.

Using a simulated monthly investment dataset and interactive Tableau dashboards, the project compares different investment strategies and evaluates whether currency timing strategies outperform passive bond investments.

The analysis highlights the difference between **nominal asset growth** and **real purchasing power** under changing macroeconomic conditions.

---

# Key Questions

1. How does investment allocation influence long-term wealth growth?
2. Can FX timing strategies outperform passive investments?
3. How do inflation and exchange rate movements affect real wealth?

---

# Project Structure

The project consists of three analytical dashboards:

## 1. Investment Strategy Simulator

An interactive dashboard that allows users to adjust:

- Investment allocation ratio
- Annual return assumptions for two investment products

It compares:

Nominal Wealth vs Real Wealth (inflation adjusted)

Key insight:

Nominal wealth appears to grow steadily, but once inflation and currency depreciation are considered, real purchasing power grows much slower.

The effect is especially visible during the **2022–2024 inflation spike**.

---

## 2. FX Timing Strategy

This dashboard tests a rule-based currency exchange strategy using a **3-month rolling average of the EUR/HUF exchange rate**.

FX conversion is triggered when the current exchange rate is more favorable than the recent average.

Key finding:

FX timing opportunities are rare.  
Between 2020 and 2024, the strategy generates less than **€300 of additional value**, significantly underperforming a simple **5% bond investment strategy**.

---

## 3. Macroeconomic Drivers

This dashboard visualizes yearly and monthly trends in:

- Inflation
- EUR/HUF exchange rate
- Real vs nominal asset value

Key insight:

Exchange rates and inflation do not move together consistently.  
The year **2022** represents the most severe macroeconomic shock, with both high inflation and strong HUF depreciation.

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

# Dashboard

Interactive Tableau dashboard:

[Insert Tableau Public Link]

---

# Documentation

Full methodology and modeling decisions are available here:

documentation/HUF_Investment_Project_Documentation.pdf

The documentation includes:

- Model design decisions
- Calculation logic
- Tableau limitations and workarounds
- Key insights and limitations

---

# Key Takeaway

The project demonstrates that **nominal asset growth can be misleading**.  
When inflation and currency depreciation are considered, real wealth growth can be significantly lower than expected.
