# n8n-todoist-notion-sync
A todoist-notion 2-way sync workflow for n8n.

It's based on [this workflow](https://n8n.io/workflows/2772-realtime-notion-todoist-2-way-sync-with-redis/), featuring critical fixes for API version mismatches and a daily task that refreshes Redis keys to prevent free-tier Redis services from automatically spinning down due to inactivity.

