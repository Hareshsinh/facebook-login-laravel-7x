# login using facebook 

## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/5.5/installation#installation)

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Install all the dependencies using composer

    composer install

Generate a new application key

    php artisan key:generate

Run migration for add database tables

    php artisan migrate
using this link make client id and secret    

    https://developers.facebook.com/
    
setup facebook keys in .env files 


    'facebook' => [
        'client_id' => 'xxx',
        'client_secret' => 'xxx',
        'redirect' => ${APP_URL}/login/facebook/callback,
    ],
    
for run the project

    php artisan ser
