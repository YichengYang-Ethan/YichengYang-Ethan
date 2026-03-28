<div align="center">

### Hey, I'm Ethan 👋

**CS & Economics @ UIUC | Quantitative Research | ML for Finance**

[![GitHub Stats](https://awesome-github-stats.azurewebsites.net/user-stats/YichengYang-Ethan?cardType=level-alternate&theme=github-dark&preferLogin=false)](https://git.io/awesome-stats-card)

🔬 Building quantitative tools for systematic trading & portfolio risk management

📄 [Resume](./Yicheng_Yang_Resume.pdf) · [LinkedIn](https://linkedin.com/in/ethan85) · [yy85@illinois.edu](mailto:yy85@illinois.edu)

---

</div>

#### 🏗️ What I Build

An interconnected ecosystem of quantitative finance tools — from academic theory to production trading systems:

| Project | Description | Highlights |
|---------|-------------|------------|
| [`oracle3`](https://github.com/YichengYang-Ethan/oracle3) | Autonomous on-chain prediction market trading agent across Solana, Polymarket & Kalshi | 10 strategies (8 arb + 2 model-driven) · Wang Transform pricing engine with empirical coefficients from 291K contracts · model-informed Kelly sizing · correlation-aware risk · live dashboard |
| [`prediction-market-pricing`](https://github.com/YichengYang-Ethan/prediction-market-pricing) | Academic paper: *Pricing Prediction Markets — Risk Premiums, Incomplete Markets, and a Decomposition Framework* | Wang Transform MLE on **291K contracts across 6 platforms** · λ = 0.183 (p < 10⁻¹⁵) · favorite-longshot bias derived as theorem · full replication package |
| [`coinjure`](https://github.com/ulab-uiuc/prediction-market-cli) | Agent-native prediction market trading CLI — discover, backtest & deploy strategies | ~50 parallel strategies · Kelly allocation · spread trading with structural pair detection · [PyPI](https://pypi.org/project/coinjure/) |
| [`Market-Bubble-Index`](https://github.com/YichengYang-Ethan/Market-Bubble-Index-Dashboard) | 7-indicator composite bubble risk dashboard with drawdown probability model | AUC 0.802 for >10% drawdown prediction · Lasso + Bayesian + EVT 3-layer model · [Live Dashboard](https://yichengyang-ethan.github.io/Market-Bubble-Index-Dashboard/) |
| [`QuantPath`](https://github.com/MasterAgentAI/QuantPath) | Open-source MFE application toolkit — profile eval, school ranking & admission prediction | Logistic regression on **6,984 admission records** · 28 programs · portfolio optimizer · Claude-powered advising |
| [`clawdfolio`](https://github.com/YichengYang-Ethan/clawdfolio) | Production portfolio toolkit — multi-broker aggregation, risk analytics & options | Fama-French 3-factor · GARCH · covered call strategy (83% win rate, +3.0% α) · [PyPI](https://pypi.org/project/clawdfolio/) |

<details open>
<summary><b>🔗 How They Connect</b></summary>

```
RESEARCH       prediction-market-pricing
               Wang Transform MLE · 291K contracts · 6 platforms
               ┃
               ┃  calibrated λ per platform / category / contract
               ▼
PRICING        oracle3/pricing
               Real-time fair value · Model Greeks · Kelly sizing
               ┃
          ┌────┸────────────────────┐
          ▼                         ▼
EXECUTION oracle3                coinjure
          10 strategies            ~50 parallel strategies
          3 exchanges              Discover → backtest → deploy
          On-chain (Solana)        LLM-enhanced sizing
          ┃                         ┃
          └────────┰────────────────┘
                   ▼
RISK       clawdfolio + Market-Bubble-Index
           Correlation-aware limits · Bubble regime detection
           Portfolio analytics · Macro alerts
```

</details>

---

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
