# Market Updates v4.0

A real-time financial knowledge dashboard built with Streamlit.

## Features
- 410 validated tickers across 9 sections (India, USA, Europe, China, ETFs, Commodities, Debt & Rates, Global Indices)
- Live price ticker, technical analysis (RSI, MACD, Bollinger Bands, ADX)
- AI-scored stock picks by 3M / 6M / 12M horizon
- Monte Carlo forecast engine with auto-correction
- Global Intelligence: geopolitical impact chains, live news feeds
- WorldMonitor live global events embed

## Setup

### Local
```bash
pip install -r requirements.txt
streamlit run app_v4_compat.py
```

### Deploy (Streamlit Community Cloud)
1. Fork / push this repo to GitHub
2. Go to share.streamlit.io
3. Select this repo → set main file to `app_v4_compat.py` → Deploy

## Files
| File | Purpose |
|---|---|
| `app_v4_compat.py` | Main application |
| `validated_tickers.json` | Ticker master data (410 tickers, 9 sections) |
| `requirements.txt` | Python dependencies |
| `.streamlit/config.toml` | App configuration & theme |

## Disclaimer
Not SEBI/SEC-registered investment advice. For educational and informational purposes only.

## Local Dev Setup
VS Code + Git workflow configured on 13 March 2026.
