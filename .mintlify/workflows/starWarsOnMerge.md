---
name: "star wars on merge"
on:
  push: 
    - repo: "paaatrrrick/docs"
      branch: "main"
context:
  - repo: "paaatrrrick/personalwebsite"
  - repo: "paaatrrrick/chemistryresearch"
automerge: true
---
Add a page about star wars to my docs