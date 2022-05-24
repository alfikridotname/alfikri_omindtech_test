
# Alfikri Omnitech Test
> *For Test Backend & Laravel Developer.*

## Getting Started
This application can be installed on local server and online server with these specifications :

#### Server Requirements
1. PHP >= 8.3.0 (and meet [Laravel 9.x server requirements](https://laravel.com/docs/8.x/deployment#server-requirements)),
2. MySQL or MariaDB database,

#### Installation Steps

1. Clone the repo : `https://github.com/alfikridotname/alfikri_omindtech_test.git`
2. `$ cd alfikri_omindtech_test`
3. `$ composer install`
4. `$ cp .env.example .env`
5. `$ php artisan key:generate`
6. `$ php artisan jwt:secret`
7. Create new MySQL database for this application
8. Set database credentials on `.env` file
9. `$ php artisan migrate`
10. `$ php artisan serve`
11. Visit `http://localhost:8000` via web browser
12. Online Test `https://klinikcode.com:1000`
13. Postman URL : `https://www.getpostman.com/collections/4b77191a78b32fd7563b` 
14. Done
