# Trader Performance vs Market Sentiment – Summary

## Methodology
The analysis combines Bitcoin market sentiment data (Fear & Greed Index) with historical trader-level data from the Hyperliquid platform.  
Both datasets were cleaned, standardized, and aligned at a **daily level**. Key performance and behavioral metrics such as daily PnL, win rate, leverage usage, trade frequency, and position bias were engineered to study sentiment-driven effects.

Traders were further segmented based on:
- Trading activity (Frequent vs Infrequent)
- Risk behavior (High vs Low leverage)

---

## Key Insights

1. **Performance differs significantly across sentiment regimes**  
   Traders achieve higher average PnL and win rates during **Greed** days, while **Fear** days are associated with lower profitability and higher downside risk.

2. **Trader behavior changes with sentiment**  
   - Greed days show increased trade frequency and higher leverage usage  
   - Fear days lead to reduced trading activity and more conservative position sizing

3. **Risk amplification during Fear periods**  
   High-leverage traders experience disproportionately larger losses during Fear days, indicating that aggressive risk-taking performs poorly under negative sentiment.

---

## Actionable Strategy Recommendations

### Strategy 1: Risk Reduction During Fear
- Reduce leverage exposure by 30–50%
- Limit trading to historically consistent and low-volatility traders
- Avoid high-frequency or aggressive strategies during Fear sentiment

### Strategy 2: Controlled Expansion During Greed
- Allow higher trade frequency for frequent traders
- Permit moderate leverage increases while enforcing leverage caps
- Actively monitor high-risk traders to prevent excessive drawdowns

These rules can be directly implemented as **sentiment-aware trading constraints** to improve risk-adjusted performance.

---

## Conclusion
Market sentiment plays a critical role in shaping trader behavior and outcomes. Incorporating sentiment-aware controls into trading strategies can significantly improve performance consistency and risk management, particularly during periods of elevated market fear.
