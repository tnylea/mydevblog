---
title: Understanding Promises in JavaScript
description: A beginner-friendly guide to JavaScript Promises and how they work.
created_at: 2025-05-03 22:31:39
updated_at: 2025-05-03 22:31:39
---

Promises represent the eventual completion (or failure) of an asynchronous operation.

```js
fetch('/api/data')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

### Key points:
- `.then()` handles success
- `.catch()` handles errors
- Promises help avoid callback hell
