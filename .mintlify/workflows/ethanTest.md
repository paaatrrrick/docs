---
name: "Vale style audit"
on:
  cron: "2 14 * * 3"
---

Run a Vale style audit on all MDX files in the repo using the Vale configuration in `.vale/`. Flag any errors or warnings.