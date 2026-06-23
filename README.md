# FinanceBroski — Quant Developer

I build the tools systematic traders actually need — and I understand markets, not just code.

I specialize in **trading bots, strategy backtesting, market dashboards, and financial-data pipelines**. My focus is the difference between a backtest that *looks* good and one that's *real* — the strategies I build come with honest statistics, not curve-fit fantasies.

## What I build

- **Trading bots & Expert Advisors** (Python, MT5/MT4) with real risk controls — position sizing, daily-loss limits, prop-firm rules
- **Strategy backtesting** — survivorship-free, realistic costs, deflated-Sharpe / walk-forward screening
- **Trading dashboards & data pipelines** — Python · FastAPI · React
- **AI automation & LLM integration** (GPT / Claude / Gemini APIs) — document pipelines, scheduled jobs, workflow automation with verification built in

## Featured projects

- **[pit-data-sample](https://github.com/Finance-broski/pit-data-sample)** — a free, real-data sample of a survivorship-free, point-in-time NSE/BSE dataset: delisted names included, fundamentals stamped with their real announcement date, CA-adjusted total-return prices. Ships with a runnable notebook and a worked case study — the same vanilla value screen "earns" **~+4 pp/yr** more once you let it cheat with survivorship + look-ahead bias. CC-BY 4.0.
- **[nse-factor-backtest](https://github.com/Finance-broski/nse-factor-backtest)** — research-grade factor backtester with a pre-registered, one-shot held-out test that **rejected its own strategy**. Most repos show winners; this one shows the machinery.
- **[nse-fundamental-screener](https://github.com/Finance-broski/nse-fundamental-screener)** — ranks stocks by Magic Formula / Quality / Piotroski F-Score from primary balance-sheet data.
- **[kite-execution-pipeline](https://github.com/Finance-broski/kite-execution-pipeline)** — SEBI-compliant Zerodha execution layer: target-diff orders, limit-only, human-in-the-loop, 11 tests.
- **[quant-cockpit](https://github.com/Finance-broski/quant-cockpit)** — real-time trading dashboard (live equity, positions, risk) in React + FastAPI.

> The point-in-time reconstruction pipeline behind the data — bhavcopy + corporate actions + XBRL, ~29k filings across 1,300+ names — is proprietary. **[pit-data-sample](https://github.com/Finance-broski/pit-data-sample)** is exactly what it produces; diff it against whatever you use today, or [open an issue](https://github.com/Finance-broski/pit-data-sample/issues) to have it measured on your own tickers.
