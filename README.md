<div align="center">

### Hey, I'm Ethan 👋

**CS + Statistics + Economics @ UIUC | Prediction Market Pricing & Autonomous Trading**

[![GitHub Stats](https://awesome-github-stats.azurewebsites.net/user-stats/YichengYang-Ethan?cardType=level-alternate&theme=github-dark&preferLogin=false)](https://git.io/awesome-stats-card)

🔬 Research: risk premium decomposition via distortion risk measures · Production: autonomous trading agents across 3 prediction market exchanges

📄 [Resume](./Yicheng_Yang_Resume.pdf) · [LinkedIn](https://linkedin.com/in/ethan85) · [yy85@illinois.edu](mailto:yy85@illinois.edu)

---

</div>

#### 🏗️ What I Build

| Project | Description | Highlights |
|---------|-------------|------------|
| [`oracle3`](https://github.com/YichengYang-Ethan/oracle3) | Autonomous prediction market trading agent — Solana, Polymarket & Kalshi | 8 probability-axiom arbitrage strategies + 2 model-driven · Wang Transform pricing engine (deploys paper's exact coefficients) · Kelly sizing via model Greeks · correlation-aware risk |
| [`prediction-market-pricing`](https://github.com/YichengYang-Ethan/prediction-market-pricing) | Working paper: *Pricing Prediction Markets — Risk Premiums, Incomplete Markets, and a Decomposition Framework* | Wang Transform MLE on **291K contracts, 6 platforms** · λ = 0.183 (p < 10⁻¹⁵) · favorite-longshot bias derived as theorem · hierarchical covariate model · time-varying premium decay |
| [`coinjure`](https://github.com/ulab-uiuc/prediction-market-cli) | Agent-native prediction market CLI (UIUC ulab) — discover, backtest & deploy | Cross-platform relation discovery (8 types) · ~50 parallel strategies · Kelly allocation · [![PyPI](https://img.shields.io/pypi/v/coinjure.svg)](https://pypi.org/project/coinjure/) |
| [`Market-Bubble-Index`](https://github.com/YichengYang-Ethan/Market-Bubble-Index-Dashboard) | Drawdown probability model with 7-indicator composite bubble index | AUC 0.802 · Lasso + Bayesian + EVT/GPD ensemble · GSADF bubble detection · [Live Dashboard](https://yichengyang-ethan.github.io/Market-Bubble-Index-Dashboard/) |
| [`clawdfolio`](https://github.com/YichengYang-Ethan/clawdfolio) | Portfolio analytics toolkit — multi-broker aggregation, risk & options | Fama-French 3-factor · GARCH · covered call strategy (83% win rate, +3.0% α) · [![PyPI](https://img.shields.io/pypi/v/clawdfolio.svg)](https://pypi.org/project/clawdfolio/) |
| [`QuantPath`](https://github.com/MasterAgentAI/QuantPath) | MFE application toolkit — admission prediction & program ranking | Logistic regression on **6,984 admission records** · 28 programs · portfolio optimizer |

<details open>
<summary><b>🔗 How They Connect</b></summary>

The paper's exact λ estimates and covariate model are deployed as `oracle3`'s pricing engine — this is the one genuine theory-to-production pipeline:

```
prediction-market-pricing ──► oracle3/pricing ──► oracle3 strategies
(MLE: λ, covariate betas,     (real-time fair value,   (10 strategies,
 time-varying decay)            Greeks, Kelly sizing)    3 exchanges)
```

`coinjure` shares the prediction market domain and relation-discovery infrastructure with `oracle3`. `clawdfolio` and `Market-Bubble-Index` are independent equity/options projects.

</details>

---

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat&logo=solana&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat&logo=pypi&logoColor=white)

</div>
