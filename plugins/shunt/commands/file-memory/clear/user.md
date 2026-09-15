---
description: Clear the Shunt USER store and invalidate its session snapshots
---

Use the shunt file-memory skill. Show the user the current user entries from
`memory list --root "$PWD" --target user` and confirm before running
`memory clear --root "$PWD" --target user --confirm`. This removes every user
entry and invalidates plugin-managed snapshots so erased entries are not restored
later; the other store, unrelated configuration and the cache are untouched. Text
already delivered to an open conversation cannot be retracted by a file operation.
