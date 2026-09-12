# CHN50 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-47_068_rows-blue)](https://getdata.finance/datasets/chn50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/chn50)

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
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/chn50) · **47,068** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `CHN50_1h.csv` (2,638 rows, `2026-03-12` -> `2026-09-11`, 223.97 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/chn50)** — **47,068** `1h` rows (full `1m`: 2,664,006), **11 timeframes**, `2017-07-17` -> `2026-09-11`.

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
| 1h rows | 2,638 | **47,068** |
| Size | 223.97 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/chn50) |
| Period | `2026-03-12` -> `2026-09-11` | `2017-07-17` -> `2026-09-11` |
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
| 2026-03-12T03:00:00+00:00 | 14827.23 | 14837.21 | 14787.21 | 14795.21 | 6622 |
| 2026-03-12T04:00:00+00:00 | 14795.21 | 14803.73 | 14790.21 | 14792.22 | 525.65492 |
| 2026-03-12T05:00:00+00:00 | 14792.22 | 14848.22 | 14773.71 | 14846.71 | 7812 |
| 2026-03-12T06:00:00+00:00 | 14846.71 | 14883.23 | 14839.21 | 14858.21 | 6290 |
| 2026-03-12T07:00:00+00:00 | 14858.21 | 14877.22 | 14853.21 | 14876.23 | 1420 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T16:00:00+00:00 | 14532.46 | 14538.46 | 14521.45 | 14527.46 | 616 |
| 2026-09-11T17:00:00+00:00 | 14527.46 | 14530.46 | 14520.45 | 14522.46 | 420 |
| 2026-09-11T18:00:00+00:00 | 14522.46 | 14525.97 | 14511.96 | 14514.47 | 338 |
| 2026-09-11T19:00:00+00:00 | 14514.47 | 14517.47 | 14510.45 | 14512.46 | 297 |
| 2026-09-11T20:00:00+00:00 | 14512.46 | 14513.47 | 14508.45 | 14510.47 | 87 |

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

The complete **CHN50** archive on **[getdata.finance](https://getdata.finance/datasets/chn50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **47,068** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full CHN50 dataset on getdata.finance](https://getdata.finance/datasets/chn50)**

---
*GetData · CHN50 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/chn50)*
