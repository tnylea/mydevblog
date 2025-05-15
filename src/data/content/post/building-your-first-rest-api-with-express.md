---
title: Building Your First REST API with Express
description: Step-by-step guide to building a REST API using Express.js.
created_at: 2025-05-03 22:31:39
updated_at: 2025-05-03 22:31:39
---

Express is a minimal Node.js framework.

```js
const express = require('express');
const app = express();

app.get('/api', (req, res) => {
  res.json({ message: 'Hello API' });
});

app.listen(3000, () => console.log('Server running'));
```

Start small, then expand with routers, middleware, and error handling!
