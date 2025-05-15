---
title: Unit Testing in Laravel
description: A quick guide to writing unit tests in a Laravel project.
created_at: 2025-05-03 22:36:16
updated_at: 2025-05-03 22:36:16
---

Laravel uses PHPUnit for testing.

```bash
php artisan make:test ExampleTest
```

Example test:

```php
public function test_example()
{
    $response = $this->get('/');
    $response->assertStatus(200);
}
```

Run tests with:

```bash
php artisan test
```
