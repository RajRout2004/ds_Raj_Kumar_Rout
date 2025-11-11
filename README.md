# ds_Raj_Kumar_Rout

This repository contains my Data Science assignment analyzing the relationship between **trader behavior** and **Bitcoin market sentiment (Fear vs Greed)**.

---

## 📘 Project Overview
The objective of this project is to explore how **trading behavior** — such as profitability, volume, and risk — aligns or diverges from overall **market sentiment**.  
Two datasets were analyzed:

1. **Bitcoin Market Sentiment Dataset**  
   - Columns: `Date`, `Classification` (Fear / Greed)

2. **Historical Trader Data (Hyperliquid)**  
   - Columns: `account`, `coin`, `execution_price`, `size_usd`, `side`, `timestamp`, `closed_pnl`, etc.

The analysis identifies patterns in trader performance during different sentiment conditions and provides insights for smarter trading strategies.

---

## ⚙️ Steps Performed

1. **Data Cleaning & Preprocessing**  
   - Standardized column names, parsed timestamps, and handled missing values.

2. **Feature Engineering**  
   - Calculated daily PnL, win rates, notional values, and simple trading signals.

3. **Exploratory Data Analysis (EDA)**  
   - Visualized daily performance, trading volume, and sentiment trends.

4. **Sentiment Comparison**  
   - Compared profitability and activity under Fear vs Greed market phases.

5. **Statistical Testing**  
   - Used t-tests to check for significant performance differences between sentiments.

6. **Signal Generation**  
   - Designed a basic rule-based “Risky vs Neutral” trading signal based on sentiment and volume.

---

## 📊 Folder Structure
ds_Raj_Kumar_Rout/
├── notebook_1.ipynb # Main Colab notebook
├── csv_files/
│ ├── daily_merged_with_sentiment.csv
│ └── historical_cleaned.csv
├── outputs/
│ ├── daily_closed_pnl_sum.png
│ ├── daily_trade_count.png
│ └── pnl_by_sentiment.png
├── ds_report.pdf # Summary report (to be added)
└── README.md # Project documentation

