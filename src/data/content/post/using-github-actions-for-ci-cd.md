---
title: Using GitHub Actions for CI/CD
description: Automate your workflows with GitHub Actions for continuous integration.
created_at: 2025-05-03 22:36:16
updated_at: 2025-05-03 22:36:16
---

GitHub Actions lets you define workflows in `.github/workflows`.

```yaml
name: CI
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - run: npm install
      - run: npm test
```

Automate tests, builds, and deployments easily!
