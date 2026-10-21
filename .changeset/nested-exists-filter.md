---
"@trigger.dev/core": patch
---

Fix `bodyFilter` in `retry.fetch` not matching when a nested `$exists: false` filter sits under a parent key that is missing or null in the response body.
