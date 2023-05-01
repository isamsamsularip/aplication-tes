
## Technologies

### Frontend

* [VueJS](https://fr.vuejs.org/index.html) - A JavaScript framework for building great user interfaces.
* [Bootstrap 4](https://getbootstrap.com) - Bootstrap is the most used CSS framework.
* [Vuex](https://getbootstrap.com) - A state management library for VueJS applications and serves as a central
store for the application.

### Backend

* PHP 7.2
* SQLite3 for development and MySQL for production.
* PHPUnit for unit tests.
* [Laravel](http://www.laravel.com) - A PHP Full stack framework
* [Tymon/Jwt-auth](https://jwt-auth.readthedocs.io/en/develop/) - A library used in laravel for Json Web Token authentication

## Features

* CRUD (create / read / update / delete) on posts
* CRUD (create / read / update / delete ) on post categories
* Image upload for post cover
* Creating comments on post page
* Pagination on posts listing
* Searching on posts
* Authentication for the admin
## Prerequisites

* PHP 7.2
* SQLite3
* Git
* Composer

## Getting Started

* Clone the project from Github

          $ git clone https://github.com/isamsamsularip/aplication-tes
          $ cd aplication-tes

* Install the packages for laravel:

         aplication-tes$ composer install

* Create the database:

          aplication-tes$ touch database/database.sqlite
          
* Create the .env file :

          aplication-tes$ cp .env.example .env
        
* Generate the encryption key for Laravel :

          aplication-tes$ php artisan key:generate
        
* Add database information :

          aplication-tes$ vim .env
        
* Change the DB_CONNECTION to put sqlite :

          DB_CONNECTION=sqlite        

* Load sample records:

         aplication-tes$ php artisan migrate --seed

* Run the Laravel Server in development mode

          aplication-tes$ php artisan serve

* Start client in development mode. You should be able to go to `http://localhost:8000`

* To access to the administration panel, there is a link in the bottom of the page or go to `http://localhost:8000/login`
