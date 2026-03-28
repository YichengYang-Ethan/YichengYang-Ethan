<div align="center">

### Yicheng (Ethan) Yang

**CS + Statistics + Economics @ UIUC | Quantitative Research | Prediction Market Pricing**

[![GitHub Stats](https://awesome-github-stats.azurewebsites.net/user-stats/YichengYang-Ethan?cardType=level-alternate&theme=github-dark&preferLogin=false)](https://git.io/awesome-stats-card)

Building the theory and infrastructure for autonomous prediction market trading —
from academic pricing models to production execution systems.

[Resume](./Yicheng_Yang_Resume.pdf) · [LinkedIn](https://linkedin.com/in/ethan85) · [yy85@illinois.edu](mailto:yy85@illinois.edu)

---

</div>

#### What I Build

An interconnected ecosystem spanning academic theory, pricing engine, and autonomous trading:

| Project | Description | Highlights |
|---------|-------------|------------|
| [**oracle3**](https://github.com/YichengYang-Ethan/oracle3) | Autonomous on-chain prediction market trading agent across Solana, Polymarket & Kalshi | 10 strategies (8 arb + 2 model-driven) · Wang Transform pricing engine · Kelly sizing with model Greeks · correlation-aware risk · live dashboard · [![Stars](https://img.shields.io/github/stars/YichengYang-Ethan/oracle3?style=flat)](https://github.com/YichengYang-Ethan/oracle3) |
| [**prediction-market-pricing**](https://github.com/YichengYang-Ethan/prediction-market-pricing) | Working paper: *Pricing Prediction Markets: Risk Premiums, Incomplete Markets, and a Decomposition Framework* | Wang Transform MLE on **291,309 contracts** across 6 platforms · λ=0.183 (p<10⁻¹⁵) · favorite-longshot bias as theorem · full replication package |
| [**coinjure**](https://github.com/ulab-uiuc/prediction-market-cli) | Agent-native prediction market trading CLI (UIUC ulab) | ~50 parallel strategies · 3-tier LLM sizing · edge-weighted allocation · cross-platform relation discovery · [![PyPI](https://img.shields.io/pypi/v/coinjure.svg)](https://pypi.org/project/coinjure/) |
| [**Market-Bubble-Index**](https://github.com/YichengYang-Ethan/Market-Bubble-Index-Dashboard) | 7-indicator composite bubble risk dashboard with drawdown probability model | AUC 0.802 · Lasso + Bayesian + EVT 3-layer model · GSADF bubble detection · [Live Dashboard](https://yichengyang-ethan.github.io/Market-Bubble-Index-Dashboard/) |
| [**QuantPath**](https://github.com/MasterAgentAI/QuantPath) | Open-source MFE application toolkit — profile eval, school ranking & admission prediction | Logistic regression on **6,984 admission records** · 28 programs · portfolio optimizer |
| [**clawdfolio**](https://github.com/YichengYang-Ethan/clawdfolio) | Production portfolio analytics toolkit | Fama-French 3-factor · GARCH · covered call strategy (83% win, +3.0% α) · [![PyPI](https://img.shields.io/pypi/v/clawdfolio.svg)](https://pypi.org/project/clawdfolio/) |

<details>
<summary><b>How They Connect</b></summary>

```
  prediction-market-pricing          (Theory: Wang Transform, 291K-contract MLE)
          │
          │  empirical coefficients: λ=0.166 (Polymarket), 0.187 (Kalshi)
          │  covariate model: volume, duration, extremity → per-contract λ
          ▼
       oracle3/pricing                (Engine: real-time fair value, model Greeks, Kelly sizing)
          │
          │  fair value signals, edge estimation, correlation risk
          ▼
  oracle3 + coinjure                  (Execution: 10 strategies, 3 exchanges, autonomous trading)
          │
          │  portfolio monitoring, risk alerts
          ▼
  clawdfolio + Market-Bubble-Index    (Risk: portfolio analytics, macro regime detection)
```

The prediction market pricing paper provides the **theoretical foundation** (why prices deviate from probabilities). Oracle3 turns that theory into a **deployable pricing engine** with exact empirical coefficients. The trading strategies then **monetize the theory** by identifying and trading mispricings in real-time across Solana, Polymarket, and Kalshi.

</details>

---

#### Research

**Pricing Prediction Markets: Risk Premiums, Incomplete Markets, and a Decomposition Framework** (Yang, 2026)

> First formal application of the Wang Transform to prediction markets. Decomposes market prices into physical probability + risk premium via a single-parameter probit distortion, calibrated on 291,309 contracts across Polymarket, Kalshi, Metaculus, Good Judgment Open, INFER, and Manifold. Key findings: systematic overpricing (λ=0.183, p<10⁻¹⁵), favorite-longshot bias derived as theorem, play-money markets are *underpriced* (λ=−0.218 — natural negative control), and very-high-volume markets have λ≈0 (premium competed away by informed traders).

---

#### Skills

**Quant**: MLE, Wang Transform, Kelly criterion, cointegration, GARCH, Fama-French, VaR/CVaR, EVT/GPD, GSADF, Markov regime switching

**ML**: scikit-learn, LightGBM, XGBoost, Bayesian inference, SHAP, walk-forward CV

**Engineering**: Python, TypeScript, React, Solana/SPL, asyncio, FastAPI, Click, Poetry, PyPI

**Finance**: Prediction markets (Polymarket/Kalshi CLOB), options Greeks, portfolio optimization, volatility modeling, risk management

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat&logo=solana&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat&logo=pypi&logoColor=white)

</div>

---

<p align="center">
  <img src="./profile-summary-card-output/github_dark/0-profile-details.svg" />
</p>
