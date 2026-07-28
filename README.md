# Ayan Jain

**I measure what backtests lie about.**

Independent quantitative researcher and backtest auditor. I build systematic strategies and audit the data and code underneath them (point-in-time universes, survivorship, look-ahead, costs) before real capital is at risk.

### Published research
**[Survivorship Bias in Indian Equities is not a Number](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7099378)** (SSRN, 2026). Survivorship bias is not a single figure. I measure it at anywhere from +0.8 to +3.2 percentage points a year on the same market, driven entirely by vintage and universe-construction choices most tools never report.

### What I ship
- **[backtest-bias](https://github.com/Finance-broski/backtest-bias)**: open-source library (`pip install backtest-bias`) that flags survivor-only data in any backtest pipeline and fails your CI build when it silently goes biased. Survivorship detection and integrity gates for financial price panels.
- **[pit-data-sample](https://github.com/Finance-broski/pit-data-sample)**: point-in-time NSE/BSE data with a reproducible bias-demonstration notebook.
- **[nse-factor-backtest](https://github.com/Finance-broski/nse-factor-backtest)**: research-grade factor backtester with pre-registered testing.
- **[nse-fundamental-screener](https://github.com/Finance-broski/nse-fundamental-screener)**: Magic Formula, Quality, and Piotroski F-Score ranking on Indian equities.

### A measured example
24% of the top-500 Indian stocks (by 2015 turnover) are invisible to yfinance today: delisted, merged, or renamed with no map back. Test on the survivors only and your equity curve is built from a roster knowable only in hindsight. Full method and numbers in the [paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7099378) and on [Kaggle](https://www.kaggle.com/financebroski).

### The work
If you are about to fund, trade, or lever a strategy on the strength of a backtest, I audit it: survivorship, look-ahead, cost realism, execution feasibility, overfitting, statistical validity. One written verdict, reported vs honest numbers. Details at [finance-broski.github.io](https://finance-broski.github.io).

### Find me
[Website](https://finance-broski.github.io) | [LinkedIn](https://www.linkedin.com/in/ayanjain259) | [Substack (The Bias Ledger)](https://financebroski.substack.com) | [Kaggle](https://www.kaggle.com/financebroski) | [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7099378)
