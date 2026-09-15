---
description: Read one current Shunt memory entry by target and id
argument-hint: "memory|user <entry-id>"
---

Use the shunt file-memory skill. Run `memory read --root "$PWD" --target T --id ID`
using the target and id from $ARGUMENTS. Report the entry text, provenance, timestamps,
character count and the store revision. If the id is unknown, run `memory list` and
show the available ids instead of guessing.
