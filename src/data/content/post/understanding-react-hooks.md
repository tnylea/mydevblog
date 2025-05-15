---
title: Understanding React Hooks
description: A look into React Hooks like useState and useEffect.
created_at: 2025-05-03 22:31:39
updated_at: 2025-05-03 22:31:39
---

Hooks let you use state and lifecycle in functional components.

```js
import { useState, useEffect } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  useEffect(() => {
    document.title = `Count: ${count}`;
  }, [count]);

  return <button onClick={() => setCount(count + 1)}>Increment</button>;
}
```

Hooks simplify component logic and reuse!
