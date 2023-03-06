
# Blog 

sample dashboard for blog by filamentphp


## run project
sample dashboard for blog by filamentphp
Clone the repository

    git clone https://github.com/abdeldjabar99/blog-filament.git

Switch to the repo folder

    cd blog-filament

Install all the dependencies using composer

    composer install

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate

Start the local development server

    php artisan serve

You can now access the server at http://localhost:8000

**TL;DR command list**

    git clone https://github.com/abdeldjabar99/blog-filament.git
    cd laravel-realworld-example-app
    composer install
    cp .env.example .env
    
**Make sure you set the correct database connection information before running the migrations** [Environment variables](#environment-variables)

    php artisan migrate
    php artisan serve
