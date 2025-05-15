---
title: State Management with Redux
description: Learn how Redux helps manage application state in React.
created_at: 2025-05-03 22:37:16
updated_at: 2025-05-03 22:37:16
---

Redux centralizes your app’s state in a single store.

### Core concepts:
- Actions
- Reducers
- Store

Example:

```js
const reducer = (state = { count: 0 }, action) => {
  switch (action.type) {
    case 'INCREMENT':
      return { count: state.count + 1 };
    default:
      return state;
  }
};
```

Use Redux Toolkit to simplify setup!
