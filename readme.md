Laravel 5 / Angular example with JSON Web Token authentication
============================
This is a basic Laravel 5 app that shows how to use the most basic JWT authentication.

## Note
This app is not meant to be used in Production environment.  
It a very basic example, that lacks any kind of input validation, handling of expired tokens, local storage fallback to cookies or any other
storage.

## Installation
- Clone the repository (`git clone git@github.com:ttkalec/laravel5-angular-jwt.git`)
- Use [Laravel Homestead](http://laravel.com/docs/5.0/homestead)
- SSH in to your Homestead Vagrant box
- Run `php composer install` to install the dependencies ([get composer here](http://getcomposer.org/download/))
- Run `php artisan migrate` (to setup the database)
- Run `php artisan db:seed` (if you want some sample data)