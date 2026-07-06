# US2000 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-402_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full US2000 dataset on ork.ad**](https://ork.ad/)

**US2000 1w OHLCV Stock index historical data** — ultra high-quality 1w OHLCV for **Russell 2000**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1w OHLCV** for **Russell 2000** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **402** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `US2000_1w.csv` (105 rows, `2024-07-01` → `2026-06-29`). **Full archive on [ork.ad](https://ork.ad/)** — **402** `1w` rows (~0.02 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2018-10-22` → `2026-06-29`.

## Download sample

**[US2000_1w.csv](https://github.com/ork-ad/us2000-1w-ohlcv-index-historical-data/blob/main/US2000_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/us2000-1w-ohlcv-index-historical-data/main/US2000_1w.csv)) · [GitHub Releases](https://github.com/ork-ad/us2000-1w-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/us2000-1w-ohlcv-index-historical-data/](https://ork-ad.github.io/us2000-1w-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Russell 2000 · Stock index | Russell 2000 · Stock index |
| Timeframes | `1w` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1w rows | 105 | **402** |
| Size | 0.01 MB | ~0.02 MB |
| Period | `2024-07-01` → `2026-06-29` | `2018-10-22` → `2026-06-29` |
| File | `US2000_1w.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1w` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1w` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US2000_1w.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-07-01T00:00:00Z | 2049.76 | 2060.66 | 2015.13 | 2023.47 | 420838.0 |
| 2024-07-08T00:00:00Z | 2023.47 | 2169.5 | 2020.0 | 2150.03 | 560408.0 |
| 2024-07-15T00:00:00Z | 2150.03 | 2288.04 | 2150.03 | 2186.98 | 831843.0 |
| 2024-07-22T00:00:00Z | 2186.98 | 2275.0 | 2174.18 | 2263.6 | 905149.0 |
| 2024-07-29T00:00:00Z | 2263.6 | 2308.31 | 2085.82 | 2104.76 | 1055603.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-01T00:00:00Z | 2916.52 | 2945.72 | 2809.79 | 2811.79 | 1857689.0 |
| 2026-06-08T00:00:00Z | 2811.79 | 2972.92 | 2792.11 | 2948.57 | 3794102.0 |
| 2026-06-15T00:00:00Z | 2948.57 | 3003.93 | 2909.97 | 2974.77 | 1886978.0 |
| 2026-06-22T00:00:00Z | 2974.77 | 3042.61 | 2945.54 | 3006.05 | 2213264.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('US2000_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1D').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US2000_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('US2000_1w.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **US2000** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **402** rows at `1w`, plus all other timeframes in the same ZIP.

**[→ Get the full US2000 dataset on ork.ad](https://ork.ad/)**

---
*GetData · US2000 1w OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*