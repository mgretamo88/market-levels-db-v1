# US Equities & Indices Options Market Structure Data Feed

Daily derived options market structure levels, specifically Call Walls and Put Walls calculated from aggregated options chains for liquid US equities, ETFs, and major indices.

### Dataset Overview
- **Coverage:** 290+ liquid US equities, sector ETFs, and major market indices.
- **Update Frequency:** Daily end-of-day snapshots after US market close.
- **Data Points:** Call Wall (dominant upside resistance/positive gamma barrier) and Put Wall (dominant downside support/negative gamma barrier).

### Integration
Formatted and indexed via `seeds.json` for native integration with TradingView Pine Script via `request.seed()`.
