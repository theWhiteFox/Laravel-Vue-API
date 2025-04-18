# Laravel Vue API
 part of my learning Laravel & VueJS

Running the API

Create the database (and database user if necessary) and add them to the .env file.

DB_CONNECTION=mysql

DB_HOST=127.0.0.1

DB_PORT=3306

DB_DATABASE=your_db_name

DB_USERNAME=root

DB_PASSWORD=your_password

Then install, migrate, seed:

    composer install
    php artisan migrate
    php artisan db:seed
    php artisan serve

The API will be running on [localhost:8000/register](localhost:8000/register)

![](https://www.thewhitefox.ninja/static/bea310d577a2677c14e6f8a0d1931f7f/8711f/register.png)

8 authentication run:

    composer require laravel/ui
    php artisan ui vue
    php artisan ui bootstrap --auth

Read more here
[https://laravel.com/docs/8.x/authentication](https://laravel.com/docs/8.x/authentication)
