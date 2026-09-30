## Yicheng (Ethan) Yang

**CS + Statistics + Economics @ UIUC (4.0 GPA) · Quantitative Finance Research · GSoC 2026 @ PyMC · Founder, [Prediction@Illinois](https://prediction-illinois.github.io/)**

Research: pricing prediction markets as incomplete markets — which pricing measure the market selects, and the calibration wedge it leaves. Sole-authored working paper, presented at RBFC 2026 (VU Amsterdam) and cited in *Economics Letters*: the Wang transform as a one-parameter selection rule, estimated by MLE on 291,309 resolved contracts across 6 platforms.

[Site](https://yichengyang-ethan.github.io/) · [SSRN](https://ssrn.com/abstract=6468338) · [LinkedIn](https://linkedin.com/in/ethan85) · [yy85@illinois.edu](mailto:yy85@illinois.edu)

**Open source**: GSoC 2026 @ PyMC (Streaming Variational Inference) — out-of-core `DataLoader` for minibatch ADVI, [shipped in pymc-extras v0.15.0](https://github.com/pymc-devs/pymc-extras/pull/698) · [out-of-core minibatch ADVI on a financial tick stream](https://github.com/pymc-devs/pymc-examples/pull/892) · merged fixes to [PyMC #882](https://github.com/pymc-devs/pymc-examples/pull/882) · fix merged in [CVXPY #3256](https://github.com/cvxpy/cvxpy/pull/3256)

---

#### Projects

| Project | Description |
|---------|-------------|
| [oracle3](https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent) | Open-source trading engine and MCP server for prediction markets: fee-aware no-arbitrage checks across related event contracts, statistical arbitrage, and live or paper execution on Kalshi · Polymarket · Solana. On [PyPI](https://pypi.org/project/oracle3/) and the official MCP Registry; listed in awesome-quant. |
| [prediction-market-pricing](https://github.com/YichengYang-Ethan/prediction-market-pricing) | Replication code for the working paper — Wang-transform MLE on 291,309 resolved contracts across 6 platforms (pooled $\hat{\lambda} = 0.183$). [Interactive writeup](https://yichengyang-ethan.github.io/research) |
| [cvxpy-finance](https://github.com/YichengYang-Ethan/cvxpy-finance) | Convex portfolio-optimization cookbook — DPP-compliant mean-variance with transaction costs, Spinu risk parity (exponential cone), and Black-Litterman |
| [market-predict](https://github.com/YichengYang-Ethan/market-predict) | SPY/QQQ options-positioning dashboard — open-interest walls, dealer gamma flip (net GEX zero-crossing), max pain, and Kalshi + Polymarket implied distributions from 18 free feeds, [live on HF Spaces](https://ethanyang85-market-predict.hf.space/) |
| [clawdfolio](https://github.com/YichengYang-Ethan/clawdfolio) | Multi-broker portfolio analytics on [PyPI](https://pypi.org/project/clawdfolio/) — Fama-French 3-factor, GARCH, options Greeks, and a covered-call backtester (544 tests) |

Also co-author of [Coinjure](https://github.com/ulab-uiuc/prediction-market-cli) (UIUC U Lab), a trading-agent harness for prediction markets.

---

**Tech**: Python, NumPy, SciPy, pandas, statsmodels, scikit-learn, CVXPY, PyMC, R, asyncio, Solana
