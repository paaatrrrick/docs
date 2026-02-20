---
name: "API reference refresh"
on:
  cron: "30 6 1,15 * *"
automerge: false
---

Fetch the latest OpenAPI spec and compare it against the current API reference pages. Flag any new endpoints, deprecated fields, or parameter changes, and open a PR with the updated documentation.
