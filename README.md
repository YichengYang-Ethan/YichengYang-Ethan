# Hi, I'm Yicheng (Ethan) Yang

**CS & Economics @ UIUC | Quantitative Research | ML for Finance**

I build systematic, production-grade tools for quantitative investing — from risk analytics and signal generation to portfolio visualization and ML-driven alpha research.

---

## Quant Finance Toolkit

My open-source projects form a cohesive quantitative investment system:

```
                        ┌──────────────────────────────────────┐
                        │         Visualization Layer          │
                        │                                      │
                        │  investment-dashboard  (React/TS)    │
                        │  QQQ-200D-Dashboard    (React/TS)    │
                        └──────────────┬───────────────────────┘
                                       │ consumes
                        ┌──────────────▼───────────────────────┐
                        │           Core Engine                │
                        │                                      │
                        │  clawdfolio  (Python)                │
                        │  Multi-broker aggregation, risk      │
                        │  analytics, options strategy,        │
                        │  technical signals, smart alerts     │
                        └──────────────┬───────────────────────┘
                                       │ shared indicators
                        ┌──────────────▼───────────────────────┐
                        │          ML / Research               │
                        │                                      │
                        │  crypto-return-prediction (LightGBM) │
                        │  ESG-Stock-Prediction (Random Forest)│
                        │  Feature engineering with RSI, MACD, │
                        │  Bollinger Bands, ESG factors,       │
                        │  cross-sectional ranking             │
                        └──────────────────────────────────────┘
```

### Core Engine

| Project | Description |
|---------|-------------|
| [**clawdfolio**](https://github.com/YichengYang-Ethan/clawdfolio) | Production AI portfolio monitor — multi-broker sync (Longport, Moomoo), institutional-grade risk metrics (VaR, Sharpe, Beta, Max Drawdown), options strategy playbook with delta/gamma/margin guardrails, 20+ automated finance workflows |

### Visualization

| Project | Description |
|---------|-------------|
| [**investment-dashboard**](https://github.com/YichengYang-Ethan/investment-dashboard) | React/TypeScript portfolio dashboard — real-time P&L tracking, interactive performance charts, holdings analysis, risk radar, designed as the frontend layer for clawdfolio |
| [**QQQ-200D-Deviation-Dashboard**](https://github.com/YichengYang-Ethan/QQQ-200D-Deviation-Dashboard) | Market timing tool — monitors 200-day MA deviation with historical percentile ranking; deviations above 80th percentile historically signal high-probability pullbacks |

### ML Research

| Project | Description |
|---------|-------------|
| [**crypto-return-prediction**](https://github.com/YichengYang-Ethan/crypto-return-prediction-kaggle) | 24-hour crypto return prediction for 355 assets — LightGBM ensemble with time-series cross-validation, momentum/volatility/cross-sectional feature engineering aligned with clawdfolio's indicator framework |
| [**ESG-Driven-Stock-Value-Prediction**](https://github.com/YichengYang-Ethan/ESG-Driven-Stock-Value-Prediction) | Stock value prediction using ESG factors — Random Forest with walk-forward backtesting, combining alternative data (ESG scores) with momentum/trend indicators |

---

## Technical Focus

- **Risk & Portfolio Analytics** — VaR, CVaR, Sharpe, Beta, drawdown analysis, HHI concentration
- **Options** — Covered call & cash-secured put lifecycle management, Greeks-based guardrails
- **Signal Generation** — RSI, SMA/EMA, Bollinger Bands, 200-DMA deviation percentile
- **ML for Finance** — LightGBM, Random Forest, time-series CV, cross-sectional ranking, ESG alternative data, feature engineering
- **Infrastructure** — Multi-broker API integration, automated alerting, CI/CD pipelines

---

## Tech Stack

**Languages:** Python, TypeScript, SQL

**ML/Data:** LightGBM, scikit-learn, pandas, NumPy, yfinance

**Frontend:** React, Vite, Tailwind CSS, Recharts, Streamlit

**DevOps:** GitHub Actions, pytest, pre-commit hooks

---

*Building tools that turn market data into actionable intelligence.*
