 Portfolio Manager for Crypto Trading  
---
## Overview

The Portfolio Manager is a dynamic, strategy-switching system designed to optimize trading performance in volatile cryptocurrency markets, primarily BTC and ETH. By employing a sliding window approach and multiple strategies tailored to specific market conditions, the system dynamically adapts to ensure effective trading while mitigating risks.

---

## Components

### Portfolio Manager

A strategy selector that chooses the best-performing alpha every 7 days using a performance score based on:

- Volatility  
- Max Drawdown  
- Mean Positive Returns  
- Sharpe Ratio  

### Alphas (Strategies)

**Burning Phoenix (BTC)**  

**Technical Indicators Integration (BTC)**  

**Corroborative Integration (ETH)**  

**Indicator Maxing (ETH)**  

**Temporal Fusion Transformer (BTC & ETH)**  

**Kalman Filters (BTC & ETH)**  

---

## Risk Management

- **False Signal Mitigation**  
  Uses the Choppiness Index to avoid low-confidence trades in sideways markets

- **ATR-Based Stop-Loss and Take-Profit**  
  Adapts thresholds dynamically based on market volatility

- **Multi-Metric Evaluation**  
  Filters out riskier strategies during volatile periods using performance metrics

---

## Future Work

- Add strategies specialized for choppy/sideways market conditions  
- Improve compatibility of deep learning models (e.g., TFT) within the master alpha  
- Explore adaptive learning methods such as reinforcement learning for strategy selection  

---

