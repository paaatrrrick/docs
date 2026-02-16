---
name: "Changelog generator"
trigger:
  type: "cron"
  schedule: "0 0 * * 2"
repos:
  - "paaatrrrick/personalwebsite"
---

Read every pull request merged in `mintlify/server` and `mintlify/mint`
over the last week and update the change log. Use the update component.

For changes to the `@mintlify/validation` package that might be a bug fix
please highlight these bug fixes in the changelog under a bugfix entry.
