---
title: An Overview of GraphQL
description: Learn what GraphQL is and how it differs from REST.
created_at: 2025-05-03 22:36:16
updated_at: 2025-05-03 22:36:16
---

GraphQL is a query language for APIs.

### Key features:
- Ask for exactly the data you need
- Get multiple resources in one request
- Strongly typed schema

Example query:
```graphql
{
  user(id: 1) {
    name
    email
  }
}
```
