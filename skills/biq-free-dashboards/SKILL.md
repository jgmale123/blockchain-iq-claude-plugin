---
name: biq-free-dashboards
description: Use when the user asks for crypto market data, charts or positioning from Blockchain IQ's free dashboards (for example CFTC positioning or macro and rates).
---

1. Call biq_list_free_dashboards to get slugs and summaries.
2. Call biq_get_free_dashboard with the slug. Large dashboards omit panels; pass the panel slug to fetch one.
3. Always show the source attribution returned with the dashboard.
4. Report only what the tool returned; say when data is missing. Not financial advice.
