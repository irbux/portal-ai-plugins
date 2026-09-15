---
description: Stop Shunt memory saving and session loading without deleting entries
---

Use the shunt file-memory skill. Run `memory disable --root "$PWD"`. Report that
automatic saving and session-start loading stop, saved entries are preserved, and
status, list, read, remove, clear and delete remain available. Say that re-enabling
requires `/shunt:file-memory:setup`, and that text already delivered to this
conversation cannot be retracted by a file operation.
