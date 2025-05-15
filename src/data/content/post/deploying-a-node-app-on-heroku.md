---
title: Deploying a Node App on Heroku
description: Step-by-step guide to deploying a Node.js app on Heroku.
created_at: 2025-05-03 22:37:16
updated_at: 2025-05-03 22:37:16
---

### Steps:
1. Install Heroku CLI
2. `heroku login`
3. Create a `Procfile`:

```
web: node index.js
```

4. Push to Heroku:

```bash
git push heroku main
```

5. Open your live app:

```bash
heroku open
```
