## Yicheng (Ethan) Yang

**CS + Statistics + Economics @ UIUC (4.0 GPA) · Prediction Market Pricing · Autonomous Trading**

Research: Wang Transform applied to prediction markets — 291,309 contracts across 6 platforms, submitted to FMA 2026 Annual Meeting.

[Resume](./Yicheng_Yang_Resume.pdf) · [LinkedIn](https://linkedin.com/in/ethan85) · [yy85@illinois.edu](mailto:yy85@illinois.edu) · [Blog](https://yichengyang-ethan.github.io/)

---

#### Projects

| Project | Description |
|---------|-------------|
| [prediction-market-pricing](https://github.com/YichengYang-Ethan/prediction-market-pricing) | Working paper replication package — Wang Transform MLE, pooled $\hat{\lambda} = 0.183$ ($p < 10^{-15}$), 6 platforms |
| [oracle3](https://github.com/YichengYang-Ethan/oracle3) | Autonomous prediction market trading agent — 8 probability-axiom arbitrage + 2 model-driven strategies, 3 exchanges |
| [clawdfolio](https://github.com/YichengYang-Ethan/clawdfolio) | Portfolio analytics toolkit on [PyPI](https://pypi.org/project/clawdfolio/) — Fama-French 3-factor, GARCH, covered call (83% win rate, +3.0% alpha) |
| [Market-Bubble-Index](https://github.com/YichengYang-Ethan/Market-Bubble-Index-Dashboard) | Bubble detection model — 7-indicator composite index, Lasso + Bayesian + EVT ensemble (AUC 0.802), [live dashboard](https://yichengyang-ethan.github.io/Market-Bubble-Index-Dashboard/) |
| [coinjure](https://github.com/ulab-uiuc/prediction-market-cli) | Prediction market CLI (UIUC U-Lab) — 8 relation types, ~50 parallel strategies, [PyPI](https://pypi.org/project/coinjure/) |

#### Theory-to-Production Pipeline

The paper's exact $\lambda$ estimates and covariate model are deployed as `oracle3`'s pricing engine:

```
prediction-market-pricing ──> oracle3/pricing ──> oracle3 strategies
(MLE, covariate betas)        (fair value, Greeks)  (10 strategies, 3 exchanges)
```

`coinjure` shares prediction market infrastructure with `oracle3`. `clawdfolio` and `Market-Bubble-Index` are independent equity/options projects.

---

**Tech**: Python, NumPy, SciPy, pandas, statsmodels, scikit-learn, asyncio, Solana, Click
