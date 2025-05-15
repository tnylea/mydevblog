---
title: Setting Up ESLint and Prettier
description: Keep your code clean and consistent with ESLint and Prettier.
created_at: 2025-05-03 22:37:16
updated_at: 2025-05-03 22:37:16
---

Install both tools:

```bash
npm install --save-dev eslint prettier eslint-config-prettier
```

Initialize configs:

```bash
npx eslint --init
```

Add scripts to `package.json`:

```json
"scripts": {
  "lint": "eslint .",
  "format": "prettier --write ."
}
```

Run regularly to maintain code quality!
