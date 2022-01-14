# 03_09_21
## 03_09_21

```shell
php artisan vendor:publish --provider="Barryvdh\Debugbar\ServiceProvider"
```

## Laravel with Octane:
### Laravel with Octane:

Make sure to add LaravelDebugbar to your flush list in `config/octane.php`.

```php
    'flush' => [
        \Barryvdh\Debugbar\LaravelDebugbar::class,
    ],
```

