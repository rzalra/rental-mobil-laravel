# Laravel 10 - Rental Mobil

## Screenshots

![preview img](/preview.png)

## Donwload

Clone Projek

```bash
  git clone https://github.com/rzalra/rental-mobil-laravel.git
```

Masuk ke folder dengan perintah

```bash
  cd rental-mobil-laravel
```

-   Copy .env.example menjadi .env kemudian edit databasenya

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

```bash
    php artisan serve
```

#### Login

-   email = admin@admin.com
-   password = 123
