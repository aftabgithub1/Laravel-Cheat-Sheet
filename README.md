## Installing Laravel

### Via Laravel Installer
First, download the Laravel installer using Composer:
```php
composer global require laravel/installer 
```

### Install Laravel Globally
Create laravel project in any directory in your computer:
```php
laravel new blog 
```

### Via Composer Create-Project
Alternatively, you may also install Laravel by issuing the Composer create-project command in your terminal:
```php
composer create-project --prefer-dist laravel/laravel blog 
```
To check composer version, just type command below and press enter:
```php
composer 
```

### Local Development Server
If you have PHP installed locally and you would like to use PHP's built-in development server to serve your application, you may use the serve Artisan command. This command will start a development server at http://localhost:8000:
```php
php artisan serve
```
