# Binance Historical Data Fetcher 📊
This python script is time and effort saving for backtesting. In beginning of quant analysis, i faced issue of getting reliable data for analysis.
The script actually fetches historical candlestick (OHLCV) data from the Binance API for any crypto symbol (e.g., BTCUSDT) and saves it as a CSV.

## Features
- Supports all Binance trading pairs (spot market)
- Adjustable timeframe (e.g., 1m, 5m, 1h, 1d)
- Fetches up to 1000 candles per API call
- Automatically paginates large data
- Saves clean, structured data to a CSV

## Requirements

```bash
pip install -r requirements.txt
