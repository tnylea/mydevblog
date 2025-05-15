---
title: Async Await in JavaScript Explained
description: Learn how async/await simplifies asynchronous JavaScript code.
created_at: 2025-05-03 22:36:16
updated_at: 2025-05-03 22:36:16
---

Async/await makes asynchronous code look synchronous.

```js
async function fetchData() {
  try {
    const response = await fetch('/api/data');
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.error(error);
  }
}
```

### Benefits:
- Cleaner code
- Easier error handling
- Avoids callback chains
