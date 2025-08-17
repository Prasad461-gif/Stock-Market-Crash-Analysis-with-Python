# Stock-Market-Crash-Analysis-with-Python
Data Analysis on stock market


# 📉 Stock Market Crash Analysis with Python

This project focuses on **analyzing historical stock market crashes** using data from the Indian stock market (Sensex) and building an **Early Warning System (EWS)** to identify potential crashes.  
The analysis highlights famous crashes like **1997, 2008–2009, and 2020**, and also simulates a synthetic crash in **2025**.

---

## 🚀 Project Overview
- Cleaned and processed **30 years of historical Sensex data**.
- Calculated **daily returns, drawdowns, rolling averages, and volatility**.
- Identified **major crash events** (1997, 2008, 2020) using drawdown thresholds.
- Developed a **clustering method** to detect periods of market stress.
- Built an **Early Warning System (EWS)** using rolling return & volatility indicators.
- Simulated **synthetic 2025 data** to test pre-crash signals.

---

## 📊 Key Analysis & Visualizations
1. **Daily Returns Analysis** → Identify sudden market drops (e.g., > -5%).  
2. **Drawdown Analysis** → Measure severity of market falls vs. peak.  
3. **Crash Clusters** → Group contiguous crash periods.  
4. **Crash Period Visualization** → Detailed zoom into Sensex crashes of 1997, 2008, and 2020.  
5. **Early Warning System** → Trigger alerts when:
   - 10-day rolling mean return < **-0.5%**
   - 10-day rolling volatility > **2%**

---

## 📂 Dataset
- **Historical Data**: 30 years of Sensex data (`cleaned_sensex.csv`)  
- **Synthetic Data (2025)**: Generated using `numpy` to simulate pre-crash conditions.  

---

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy** → Data cleaning & analysis  
- **Plotly** → Interactive time-series visualizations  
- **Matplotlib/Seaborn** (optional) → Supporting plots  

---

## 📷 Sample Outputs
- Sensex Closing Prices with Daily Crash Highlights  
- Market Drawdown Over Time  
- Identified Crash Clusters  
- Crash Period Zoom (1997, 2008, 2020)  
- Early Warning Signals for 2025
