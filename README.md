Main web site of Patient Appointment Management System develop in Laravel framework

## Technology

- Core <a href="https://laravel.com">Laravel Framework</a>
- Back-end <a href="http://laravel-admin.org">Laravel Admin</a>
- In addition, free open source libraries.

## Server Requirements

The Laravel framework has a few system requirements. You should ensure that your web server has the following minimum
PHP version and extensions:

    PHP >= 8.0
    BCMath PHP Extension
    Ctype PHP Extension
    cURL PHP Extension
    DOM PHP Extension
    Fileinfo PHP Extension
    JSON PHP Extension
    Mbstring PHP Extension
    OpenSSL PHP Extension
    PCRE PHP Extension
    PDO PHP Extension
    Tokenizer PHP Extension
    XML PHP Extension

## To install/ run this project .
git pull from main branch

    git pull origin main
    composer update

#### copy and paste .env.example to .env and set db and other configuration and generate key

    copy .env.example .env
    php artisan key:generate

## Things need to do in the database

Run the following commands:

    php artisan telescope:install
    php artisan migrate
    php artisan serve

## For installing telescope run the commands
     
    composer require laravel/telescope
    php artisan telescope:install


## License test

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).