# Atlas Algo Labs — Pine Script Portfolio

Custom TradingView indicators and strategies, written in Pine Script v5/v6.

I build trading tools for traders: clean code, configurable inputs, alert conditions, and honest backtests. Non-repainting, confirmed-bar logic by default.

## Scripts in this repo

### 1. Trend Fusion Dashboard (`trend_fusion_dashboard.pine`)
Multi-timeframe trend and momentum overlay:
- Fast/Slow EMA pair (21/55) with crossover signals and trend-colored background
- Live dashboard table showing trend strength across 4 configurable timeframes (15m / 1h / 4h / D)
- RSI readout with overbought/oversold highlighting
- 4 alert conditions, including "Aligned" signals that fire only when all timeframes agree

### 2. Keltner Breakout Strategy (`keltner_breakout_strategy.pine`)
Backtestable volatility breakout system:
- Keltner Channel breakout entries with 200 EMA trend filter
- ATR-based stop loss and R-multiple take profit
- Realistic backtest settings: commission, position sizing as % of equity
- Alert conditions for automation via webhooks

## How to use
1. Open any chart on TradingView
2. Open the Pine Editor (bottom panel)
3. Paste the script, click "Add to chart"

## Hire me
I build custom versions of tools like these — your logic, your rules, delivered with documentation.

**Fiverr:** https://www.fiverr.com/atlasalgolabs

## Disclaimer
These tools are for analysis and education. Nothing here is financial advice, and past backtest results never guarantee future performance.
