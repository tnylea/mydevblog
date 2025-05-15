---
title: Setting Up a PostgreSQL Database
description: Steps to install and set up PostgreSQL for development.
created_at: 2025-05-03 22:36:16
updated_at: 2025-05-03 22:36:16
---

Install PostgreSQL:

```bash
brew install postgresql
brew services start postgresql
```

Connect:

```bash
psql postgres
```

Create a database:

```sql
CREATE DATABASE myapp;
```

You're ready to integrate it with your app!
