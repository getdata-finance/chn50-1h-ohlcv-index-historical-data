# CHN50 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-46_910_rows-blue)](https://getdata.finance/datasets/chn50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/chn50)

### -> [**Download the full CHN50 dataset on getdata.finance**](https://getdata.finance/datasets/chn50)

**CHN50 1h OHLCV index historical data** — ultra high-quality 1h OHLCV for **FTSE China A50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **FTSE China A50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/chn50) · **46,910** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `CHN50_1h.csv` (924 rows, `2026-06-29` -> `2026-09-02`, 70.20 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/chn50)** — **46,910** `1h` rows (full `1m`: 2,664,006), **11 timeframes**, `2017-07-17` -> `2026-09-02`.

## Download sample

**[CHN50_1h.csv](https://github.com/getdata-finance/chn50-1h-ohlcv-index-historical-data/blob/main/CHN50_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/chn50-1h-ohlcv-index-historical-data/main/CHN50_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/chn50-1h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/chn50-1h-ohlcv-index-historical-data/](https://getdata-finance.github.io/chn50-1h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/chn50](https://getdata.finance/datasets/chn50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/chn50))** |
|---|--:|---|
| Instrument | FTSE China A50 · Index | FTSE China A50 · Index |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 924 | **46,910** |
| Size | 70.20 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Period | `2026-06-29` -> `2026-09-02` | `2017-07-17` -> `2026-09-02` |
| File | `CHN50_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Coverage report | — | [CHN50 coverage](https://getdata.finance/coverage/chn50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/chn50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/chn50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-06-29T19:00:00+00:00 | 15478 | 15480.49 | 15468 | 15477 | 670.87252 |
| 2026-06-29T20:00:00+00:00 | 15477 | 15481.5 | 15473.49 | 15475.51 | 150.26662 |
| 2026-06-30T01:00:00+00:00 | 15475.51 | 15497.93 | 15361.93 | 15462.92 | 30687.8248 |
| 2026-06-30T02:00:00+00:00 | 15462.92 | 15517.92 | 15406.41 | 15474.92 | 26479 |
| 2026-06-30T03:00:00+00:00 | 15474.92 | 15616.43 | 15473.43 | 15580.93 | 12416 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T18:00:00+00:00 | 14739.01 | 14740.01 | 14721.99 | 14727.01 | 763 |
| 2026-09-01T19:00:00+00:00 | 14727.01 | 14739.01 | 14725.99 | 14737.5 | 793 |
| 2026-09-01T20:00:00+00:00 | 14737.5 | 14740.01 | 14734 | 14735 | 133 |
| 2026-09-02T01:00:00+00:00 | 14735 | 14735 | 14552 | 14554.01 | 15593 |
| 2026-09-02T02:00:00+00:00 | 14554.01 | 14554.51 | 14542.99 | 14543.99 | 114 |

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

df = pd.read_csv('CHN50_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('CHN50_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[getdata.finance](https://getdata.finance/datasets/chn50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **46,910** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full CHN50 dataset on getdata.finance](https://getdata.finance/datasets/chn50)**

---
*GetData · CHN50 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/chn50)*
