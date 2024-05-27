This repo refers to this changes: https://github.com/laravel/horizon/pull/223 to support base path configuration in laravel horizon.

Setup this project by run npm install if want to make changes.

Run npm run prod to compile css and js after make changes.

copy from this project public/css to your vendor/laravel/horizon/public/css

copy from this project public/js to your vendor/laravel/horizon/public/js 

copy from this project resources/views/app.blade.php to your vendor/laravel/horizon/resources/views/app.blade.php

run php artisan horizon:assets in your own project

add this variable: 'base_path' => '' to config/horizon.php
