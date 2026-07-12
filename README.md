# Ayan Jain (FinanceBroski)

**I measure what backtests lie about.**

I build point-in-time Indian equity data and audit backtests and datasets for the biases that
quietly inflate them: survivorship, look-ahead, unrealistic costs. The difference between a
backtest that *looks* good and one that is *real* is usually in the data, not the strategy, and
that gap is what I put a number on.

## The work

- **Working paper (under review at SSRN):** survivorship bias in Indian equities is not one
  number. It ranges from +0.8 to +3.2 percentage points per year depending on the universe
  vintage and the survivor definition. Same market, same method, a factor of four apart.
- **[backtest-bias](https://github.com/Finance-broski/backtest-bias):** a pip-installable library
  that checks any price panel for survivorship in one line, built on measured numbers, not folklore.
- **[pit-data-sample](https://github.com/Finance-broski/pit-data-sample):** a free, real-data
  sample of a survivorship-free, point-in-time NSE/BSE dataset (delisted names included,
  fundamentals stamped with their real announcement date, CA-adjusted total-return prices). Also
  on [Kaggle](https://www.kaggle.com/financebroski). Ships with a runnable notebook: the same
  vanilla value screen "earns" roughly +3 pp/yr more once you let it cheat with survivorship and
  look-ahead bias.
- **[nse-factor-backtest](https://github.com/Finance-broski/nse-factor-backtest):** a
  research-grade factor backtester with a pre-registered, one-shot held-out test that rejected its
  own strategy. Most repos show winners; this one shows the machinery.

Also built: an NSE fundamental screener (Magic Formula / Quality / Piotroski F-Score), a
SEBI-compliant Zerodha execution layer (target-diff orders, limit-only, human-in-the-loop), and a
real-time trading dashboard in React + FastAPI.

The point-in-time reconstruction pipeline behind the data (bhavcopy + corporate actions + XBRL
across 1,300+ names) is proprietary. pit-data-sample is exactly what it produces; diff it against
whatever you use today, or open an issue to have it measured on your own tickers.

## Work with me

**Bias Check:** send a backtest or a dataset, and within 48 hours you get a written verdict on
survivorship, look-ahead, cost realism, and marking, with what is wrong and roughly what it costs
in return terms. Fixed price. Start one here: [Bias Check intake](https://forms.gle/sAvosfHnitCBm9FD7).

Larger point-in-time data builds and audit engagements are scoped separately: email
ayanjain259@gmail.com.

Writeups and the measured numbers behind all of this: [financebroski.substack.com](https://financebroski.substack.com)

**Tech:** Python, pandas, NumPy, SciPy, FastAPI, React, MQL5, Pine Script.
