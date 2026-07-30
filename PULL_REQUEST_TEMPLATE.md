---
name: Improve README structure and add docs for long content
body: |
  Fix encoding issues, replace placeholders with summaries, add a concise TOC, and move long project/team entries into docs/ for easier maintenance.
  
  Changes:
  - README.md: concise site map and quick notes
  - docs/: project and team summaries
  - CONTRIBUTING.md: encoding and contribution guidelines
  - .gitattributes: enforce UTF-8 for markdown
  
  Please review docs/ files and restore any original text that may have been garbled.
head: "Improve README structure and add docs for long content"
base: "main"
---