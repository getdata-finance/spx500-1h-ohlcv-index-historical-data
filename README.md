# SPX500 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-103_590_rows-blue)](https://getdata.finance/datasets/spx500) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/spx500)

### -> [**Download the full SPX500 dataset on getdata.finance**](https://getdata.finance/datasets/spx500)

**SPX500 1h OHLCV index historical data** — ultra high-quality 1h OHLCV for **S&P 500**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **S&P 500** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/spx500) · **103,590** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `SPX500_1h.csv` (2,985 rows, `2026-03-10` -> `2026-09-09`, 223.38 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/spx500)** — **103,590** `1h` rows (full `1m`: 5,815,518), **11 timeframes**, `2009-01-02` -> `2026-09-09`.

## Download sample

**[SPX500_1h.csv](https://github.com/getdata-finance/spx500-1h-ohlcv-index-historical-data/blob/main/SPX500_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/spx500-1h-ohlcv-index-historical-data/main/SPX500_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/spx500-1h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/spx500-1h-ohlcv-index-historical-data/](https://getdata-finance.github.io/spx500-1h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/spx500](https://getdata.finance/datasets/spx500)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/spx500))** |
|---|--:|---|
| Instrument | S&P 500 · Index | S&P 500 · Index |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 2,985 | **103,590** |
| Size | 223.38 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Period | `2026-03-10` -> `2026-09-09` | `2009-01-02` -> `2026-09-09` |
| File | `SPX500_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Coverage report | — | [SPX500 coverage](https://getdata.finance/coverage/spx500) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/spx500)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/spx500) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`SPX500_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 6797.58 | 6807.96 | 6775.19 | 6782.69 | 63616 |
| 2026-03-10T20:00:00+00:00 | 6782.69 | 6796.16 | 6782.51 | 6792.24 | 11320 |
| 2026-03-10T22:00:00+00:00 | 6792.24 | 6792.49 | 6778.35 | 6782.62 | 4274 |
| 2026-03-10T23:00:00+00:00 | 6782.62 | 6794.73 | 6781.47 | 6792.49 | 3734 |
| 2026-03-11T00:00:00+00:00 | 6792.49 | 6808.99 | 6791.47 | 6804.12 | 12512 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-08T22:00:00+00:00 | 7673.15 | 7677.88 | 7671.86 | 7677.87 | 2088 |
| 2026-09-08T23:00:00+00:00 | 7677.87 | 7677.88 | 7668.11 | 7669.88 | 1721 |
| 2026-09-09T00:00:00+00:00 | 7669.88 | 7679.38 | 7669.74 | 7677.61 | 6536 |
| 2026-09-09T01:00:00+00:00 | 7677.61 | 7683.13 | 7676.62 | 7680.38 | 3654 |
| 2026-09-09T02:00:00+00:00 | 7680.38 | 7680.38 | 7680.38 | 7680.38 | 0 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('SPX500_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('SPX500_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('SPX500_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **SPX500** archive on **[getdata.finance](https://getdata.finance/datasets/spx500)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **103,590** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full SPX500 dataset on getdata.finance](https://getdata.finance/datasets/spx500)**

---
*GetData · SPX500 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/spx500)*
