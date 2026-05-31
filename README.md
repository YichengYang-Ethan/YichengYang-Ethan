## Yicheng (Ethan) Yang

**CS + Statistics + Economics @ UIUC (4.0 GPA) · Quantitative Finance Research · GSoC 2026 @ PyMC**

Research: pricing prediction markets as incomplete markets — measure-selection rules and risk premia. Working paper (SSRN) estimating the Wang-transform risk parameter by MLE on 291,309 resolved contracts across 6 platforms.

[Site](https://yichengyang-ethan.github.io/) · [Resume](./Yicheng_Yang_Resume.pdf) · [SSRN](https://ssrn.com/abstract=6468338) · [LinkedIn](https://linkedin.com/in/ethan85) · [yy85@illinois.edu](mailto:yy85@illinois.edu)

**Open source**: GSoC 2026 @ PyMC (Streaming Variational Inference) · merged fixes to [CVXPY #3256](https://github.com/cvxpy/cvxpy/pull/3256) and [PyMC #882](https://github.com/pymc-devs/pymc-examples/pull/882)

---

#### Projects

| Project | Description |
|---------|-------------|
| [prediction-market-pricing](https://github.com/YichengYang-Ethan/prediction-market-pricing) | Working paper (SSRN) — the Wang transform as a pricing-measure selection rule for incomplete markets; risk parameter estimated by MLE on 291,309 resolved contracts, 6 platforms (pooled $\hat{\lambda} = 0.183$, $p < 10^{-15}$). [Interactive writeup](https://yichengyang-ethan.github.io/research) |
| [cvxpy-finance](https://github.com/YichengYang-Ethan/cvxpy-finance) | Convex portfolio-optimization cookbook — DPP-compliant mean-variance with transaction costs, Spinu risk parity (exponential cone), and Black-Litterman |
| [holy-grail-tqqq](https://github.com/YichengYang-Ethan/holy-grail-tqqq) | 27-year leveraged-ETF rotation backtest, stress-tested with combinatorial purged cross-validation (López de Prado), deflated Sharpe, and a 7-check robustness suite |
| [oracle3](https://github.com/YichengYang-Ethan/oracle3) | Multi-venue prediction-market trading engine (633 tests, full CI) deploying the paper's exact Wang-transform pricing model — paper-traded across Kalshi · Polymarket · Solana |
| [Market-Bubble-Index](https://github.com/YichengYang-Ethan/Market-Bubble-Index-Dashboard) | 7-indicator composite bubble-risk index with a Bayesian drawdown model and purged walk-forward validation, [live dashboard](https://yichengyang-ethan.github.io/Market-Bubble-Index-Dashboard/) |
| [clawdfolio](https://github.com/YichengYang-Ethan/clawdfolio) | Multi-broker portfolio analytics on [PyPI](https://pypi.org/project/clawdfolio/) — Fama-French 3-factor, GARCH, options Greeks, and a covered-call backtester (544 tests) |

#### Theory-to-Production Pipeline

The working paper's $\lambda$ estimates and covariate model are deployed as `oracle3`'s pricing engine:

```
prediction-market-pricing ──> oracle3/pricing ──> oracle3 strategies
(MLE, covariate betas)        (fair value, Greeks)  (10 strategies, paper-traded)
```

`coinjure` ([UIUC U-Lab](https://github.com/ulab-uiuc/prediction-market-cli), on [PyPI](https://pypi.org/project/coinjure/)) shares oracle3's prediction-market infrastructure. `clawdfolio`, `cvxpy-finance`, and `Market-Bubble-Index` are independent equity/options projects.

---

**Tech**: Python, NumPy, SciPy, pandas, statsmodels, scikit-learn, CVXPY, PyMC, R, asyncio, Solana
