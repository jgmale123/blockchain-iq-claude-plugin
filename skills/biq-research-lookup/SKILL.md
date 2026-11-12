---
name: biq-research-lookup
description: Use when the user asks whether Blockchain IQ has coin research or a report on a coin or topic.
---

1. Call biq_list_research with query set to the coin or topic (limit and offset page results).
2. Call biq_list_reports for report cadence and latest edition dates.
3. Return titles, dates and links only; these tools return an index, not report bodies (some are paid).
4. Not financial advice.
