---
name: "Broken link checker"
on:
  cron: "0 9 * * 1"
automerge: false
---

Scan all pages in the docs for broken links, including internal cross-references, external URLs, and anchor links. Report any that return 404 or timeout, and open a PR that removes or updates the broken links.
