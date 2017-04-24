# Laravel-5.4
Laravel 5.4 Project Setup


## Create a new project
~~~~
laravel new [project name]
~~~~


## Git setup
~~~~
git init  
wget https://raw.githubusercontent.com/AntonioPrimera/Laravel-5.4/master/.gitignore  
git add --all  
git commit -m "Initial project setup"
~~~~

## PhpStorm IDE Helper

### Generate the _ide_helper.php file
~~~~
composer require --dev barryvdh/laravel-ide-helper  
php artisan clear-compiled  
php artisan ide-helper:generate  
php artisan optimize
~~~~

### Or get a pre-generated file
check out https://github.com/barryvdh/laravel-ide-helper for the latest one

For Laravel 5.4:  
~~~~
wget https://gist.githubusercontent.com/barryvdh/5227822/raw/2c73039cd2b11c2f90f22e829de0231dd3733d62/_ide_helper.php
~~~~
