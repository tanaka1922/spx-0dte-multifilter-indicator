# SPX 0DTE MultiFilter Indicator

A TradingView indicator for intraday SPX analysis, built and delivered as a client project. The source code, rules and settings belong to the client and are **not published** here. This page describes the work only.

## What was built
- A multi-timeframe trend indicator with optional momentum, volume and trend-strength filters
- Session control with a configurable timezone
- Projected take-profit / stop-loss levels, exit handling, an on-chart dashboard and alerts
- Debug values in the Data Window for checking past bars

## My role
- Designed the layered structure (trend trigger → session gate → optional filters → signal → exits → dashboard)
- Revised it over several versions (see [`docs/DEVELOPMENT_HISTORY.md`](docs/DEVELOPMENT_HISTORY.md)), including session-boundary handling and exit ordering
- Removed client-specific references for this portfolio page

## Known limitations
- Pine `table` dashboards update on the last bar; past bars are checked through Data Window values.
- Indicator outputs are for analysis support; validate with paper trading before any live use.

## Disclaimer
For learning and research only. Not a trading recommendation, and no profit is guaranteed.
このページは制作実績の説明です。売買のおすすめや利益の保証ではありません。ソースコード・条件・設定値は納品先のものなので公開していません。
