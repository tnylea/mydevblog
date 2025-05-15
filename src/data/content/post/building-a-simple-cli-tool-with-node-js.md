---
title: Building a Simple CLI Tool with Node.js
description: Create your own command-line interface using Node.js.
created_at: 2025-05-03 22:37:16
updated_at: 2025-05-03 22:37:16
---

Start with a basic script:

```js
#!/usr/bin/env node
console.log('Hello from your CLI!');
```

Make it executable:

```bash
chmod +x index.js
```

Add to `package.json`:

```json
"bin": {
  "mycli": "./index.js"
}
```

Publish to npm to share!
