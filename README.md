# Sites & Links MVC Web App

Tutorial to use PHP, Laravel and built-in Auth:  
https://laravel-news.com/your-first-laravel-application

- Laravel Scaffold ✅
- Database Setup ✅
- Authentication Scaffolding - builtin package ✅
- Building a List of Links ✅
- Routing and Views ✅
- Displaying the Link Submission Form ✅
- Submitting the Form ✅
- Testing the Form Submission ✅
- Testing Saving a Valid Link ✅
- Testing Failed Validation ✅ ️
- Testing URL Validation  ✅ 
- Testing Max Length Validation ✅ 
- Conclusion ✅ 

## Notes for Development 

- `php artisan serve` - start a local host development server at http://127.0.0.1:8000
- `php artisan make:model Models/{ModelName} -m` - create model and migration 
- `php artisan migrate` - run database migrations
- `php artisan make:seeder {ClassName}` - create database seeder
- `php artisan db:seed` - run database seeders
- `php artisan make:controller {ControllerName} --resource` - create controller
- `php artisan make:test {FeatureNameTest}` - create a feature test file
- `php artisan make:test {FeatureNameTest}` - create a feature test file
- `php artisan test` - run phpunit test suit

## Authentication Scaffolding
- Laravel separate first-party package to generate common Auth scaffolding
- `composer install laravel/ui` / `composer require laravel/ui` - install the UI composer package
 - `php artisan ui bootstrap --auth` - generate routes, controllers, views, and other files necessary for auth
 
 - `npm install` - compile our CSS UI
 - `npm run dev` - build dev assets; or
 - `npm run watch` - use a watcher to listen for files changes to JS and CSS files, and automatically update them. You can have this running in a separate tab while developing.
 
 -----------------