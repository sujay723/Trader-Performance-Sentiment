# Trader Performance vs Market Sentiment  
Data Science Intern – Round-0 Assignment

---

## Project Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear vs Greed)** and **trader behavior and performance** on the Hyperliquid trading platform.

The goal is to identify how sentiment influences trading outcomes and behavior, and to derive **actionable, data-driven trading strategies** that can be applied in real trading systems.

---

## Objectives
- Analyze trader performance (PnL, win rate) across Fear and Greed days
- Study changes in trader behavior based on market sentiment
- Segment traders based on activity and risk characteristics
- Propose actionable trading rules based on insights

---

## Datasets

### 1. Bitcoin Market Sentiment (Fear & Greed Index)
- **Columns:** `date`, `classification`
- **Description:** Daily Bitcoin market sentiment classified as Fear or Greed

### 2. Historical Trader Data (Hyperliquid)
- **Key Columns:**  
  `account`, `symbol`, `side`, `size`, `leverage`, `closedPnL`, timestamp column
- **Description:** Trade-level execution data for multiple traders

---

## Tools & Technologies
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn (optional – bonus)

---

## Methodology

### 1. Data Preparation
- Loaded both datasets
- Inspected shape, missing values, and duplicates
- Removed duplicate trade records
- Standardized column names
- Converted timestamps and aligned both datasets at **daily level**

### 2. Feature Engineering
Created the following metrics:
- Daily PnL per trader
- Win rate
- Average trade size
- Average leverage
- Number of trades per day
- Long/Short ratio

### 3. Analysis
- Compared trader performance between Fear and Greed days
- Analyzed behavior changes in leverage, trade frequency, and position size
- Segmented traders into:
  - Frequent vs Infrequent traders
  - High vs Low leverage traders

### 4. Visualization
- PnL distribution by sentiment
- Average leverage by sentiment
- Trading activity comparison charts

---

## Key Insights
- Traders generally achieve **higher average PnL during Greed** days
- **Leverage and trade frequency increase** during Greed sentiment
- Fear days show **reduced trading activity** and higher downside risk
- High-leverage strategies perform poorly during Fear periods

---

## Actionable Recommendations

### Strategy 1: Risk Control During Fear
- Reduce leverage by 30–50%
- Restrict trading to consistent, low-volatility traders
- Avoid high-frequency trading during Fear days

### Strategy 2: Controlled Aggression During Greed
- Allow increased trade frequency
- Permit moderate leverage increases
- Enforce leverage caps for high-risk traders

These strategies can be implemented as **sentiment-aware trading rules**.

---

## Project Structure

```text
trader-performance-sentiment/
│
├── analysis.ipynb
├── README.md
├── requirements.txt
├── figures/
│   ├── pnl_fear_vs_greed.png
│   ├── leverage_by_sentiment.png
│
└── summary.md

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/trader-performance-sentiment.git
cd trader-performance-sentiment




