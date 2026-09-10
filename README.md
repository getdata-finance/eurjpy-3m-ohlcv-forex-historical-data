# EURJPY 3m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_081_149_rows-blue)](https://getdata.finance/datasets/eurjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurjpy)

### -> [**Download the full EURJPY dataset on getdata.finance**](https://getdata.finance/datasets/eurjpy)

**EURJPY 3m OHLCV forex historical data** — ultra high-quality 3m OHLCV for **Euro / Japanese Yen**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **Euro / Japanese Yen** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurjpy) · **3,081,149** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `EURJPY_3m.csv` (62,546 rows, `2026-03-10` -> `2026-09-09`, 6.16 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurjpy)** — **3,081,149** `3m` rows (full `1m`: 9,199,932), **11 timeframes**, `2001-11-28` -> `2026-09-09`.

## Download sample

**[EURJPY_3m.csv](https://github.com/getdata-finance/eurjpy-3m-ohlcv-forex-historical-data/blob/main/EURJPY_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurjpy-3m-ohlcv-forex-historical-data/main/EURJPY_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurjpy-3m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurjpy-3m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurjpy-3m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurjpy](https://getdata.finance/datasets/eurjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurjpy))** |
|---|--:|---|
| Instrument | Euro / Japanese Yen · Forex | Euro / Japanese Yen · Forex |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 62,546 | **3,081,149** |
| Size | 6.16 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurjpy) |
| Period | `2026-03-10` -> `2026-09-09` | `2001-11-28` -> `2026-09-09` |
| File | `EURJPY_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurjpy) |
| Coverage report | — | [EURJPY coverage](https://getdata.finance/coverage/eurjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurjpy)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/eurjpy) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURJPY_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T18:33:00+00:00 | 185.791 | 185.808 | 185.724 | 185.746 | 2894 |
| 2026-03-10T18:36:00+00:00 | 185.746 | 185.801 | 185.745 | 185.773 | 3534 |
| 2026-03-10T18:39:00+00:00 | 185.773 | 185.795 | 185.75 | 185.75 | 2628 |
| 2026-03-10T18:42:00+00:00 | 185.75 | 185.811 | 185.75 | 185.792 | 2642 |
| 2026-03-10T18:45:00+00:00 | 185.792 | 185.82 | 185.765 | 185.802 | 1492 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T01:48:00+00:00 | 178.679 | 178.693 | 178.643 | 178.677 | 1241 |
| 2026-09-09T01:51:00+00:00 | 178.677 | 178.703 | 178.671 | 178.683 | 1172 |
| 2026-09-09T01:54:00+00:00 | 178.683 | 178.69 | 178.616 | 178.626 | 1194 |
| 2026-09-09T01:57:00+00:00 | 178.626 | 178.632 | 178.588 | 178.6 | 1869 |
| 2026-09-09T02:00:00+00:00 | 178.6 | 178.61 | 178.584 | 178.609 | 387 |

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

df = pd.read_csv('EURJPY_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURJPY_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EURJPY_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **EURJPY** archive on **[getdata.finance](https://getdata.finance/datasets/eurjpy)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **3,081,149** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURJPY dataset on getdata.finance](https://getdata.finance/datasets/eurjpy)**

---
*GetData · EURJPY 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurjpy)*
