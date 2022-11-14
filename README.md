## About LEP

Laravel Eloquent ✕ PostgreSQL

- [Laravel](https://laravel.com/docs/)
- [Eloquent](https://laravel.com/docs/eloquent)
- [PostgreSQL](https://www.postgresql.org/)

## Install from source
```bash
git clone git@github.com:officebiz/lep lep
cd lep
cp .env.example .env

composer install
php artisan key:generate
php artisan storage:link
```

Setup PostgreSQL database parameters
```
DB_HOST=
DB_PORT=5432
DB_DATABASE=lep
DB_USERNAME=
DB_PASSWORD=
```

Migrate database
```bash
php artisan migrate
```

Start laravel server
```bash
php artisan serve
```

## License

[MIT license](https://opensource.org/licenses/MIT)
