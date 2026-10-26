# Cooking

A cooking journal published at https://slackermandan.com/Cooking/.

## Adding a page

Create a Markdown file (in the root or a folder per food type, e.g. `bread/sourdough-2026-11-01.md`) with this front matter:

```
---
layout: default
title: Sourdough, attempt 3
date: 2026-11-01
entry: true
---
```

Any page with `entry: true` is listed automatically, oldest first, on the Cooking landing page and on the Cooking card on slackermandan.com (via `pages.json`).
