# blog-laravel-project
blog-laravel-project
#install laravel
  composer global require laravel/installer
  laravel new example-app
  cd example-app
  php artisan serve

php artisan make:controller UserController
php artisan make:component Header
php artisan make:middleware checkAge
php artisan make:model UserModel
php artisan make:migration create_test_table
php artisan migrate
php artisan migrate:reset
php artisan migrate:rollback
php artisan migrate:rollback --step 2
php artisan migrate:refresh
php artisan make:seeder MemberSeeder
php artisan db:seed --class=MemberSeeder


#middleware
  global middleware
  grouped middleware
  routeed middleware

#Http method 
  GET
  POST 
  PUT 
  HEAD 
  DELATE 
  PETCH 
  OPTIONS
