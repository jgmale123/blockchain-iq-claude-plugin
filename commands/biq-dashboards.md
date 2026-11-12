---
description: List the free Blockchain IQ dashboards, or open one by slug
---

1. If $ARGUMENTS is empty, call biq_list_free_dashboards and list slug, title and summary as a numbered list.
2. Otherwise call biq_get_free_dashboard with slug $ARGUMENTS and list its panels (slug, title, kind) with the source attribution. Fetch a panel's data only when asked, by calling again with panel set to its panelSlug.
