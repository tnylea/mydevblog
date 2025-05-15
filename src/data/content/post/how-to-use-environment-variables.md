---
title: How to Use Environment Variables
description: Manage sensitive data using .env files and environment variables.
created_at: 2025-05-03 22:37:16
updated_at: 2025-05-03 22:37:16
---

Install dotenv:

```bash
npm install dotenv
```

Create a `.env` file:

```
API_KEY=yourapikey
```

Load it in code:

```js
require('dotenv').config();
console.log(process.env.API_KEY);
```

Never commit `.env` files to version control!
