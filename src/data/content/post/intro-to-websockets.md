---
title: Intro to WebSockets
description: Understanding real-time communication using WebSockets.
created_at: 2025-05-03 22:36:16
updated_at: 2025-05-03 22:36:16
---

WebSockets allow two-way communication between client and server.

### Use cases:
- Chat applications
- Live updates
- Real-time analytics

Example with Socket.IO:

```js
const socket = io();
socket.on('message', (msg) => {
  console.log(msg);
});
```
