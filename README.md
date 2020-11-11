# Laravel Terminal Commands
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

## Project Commands
### Make a Model with migration
```php
php artisan make:model Name -m
```

### Make a Controller
```php
php artisan make:controller NameController
```

### Make a Resourceful Controller
```php
php artisan make:controller NameController -resource
// or
php artisan make:controller NameController -r
```

### Make a Model with migration and Controller
```php
php artisan make:model Name -mc
```

### Make a Model with migration and Resourceful Controller
```php
php artisan make:model Name -mcr
```

### Install Laravel User Interface for Bootstrap 4
It's very simple way to install Bootstrap 4 using laravel ui composer package. laravel ui package add laravel 8 support.
```php
composer require laravel/ui
```

### Install Bootstrap 4
After successfully install above package then we are ready to install bootstrap 4 with our application.
```php
php artisan ui bootstrap
```
We can install two way, one is a simple bootstrap 4 setup install and another is install bootstrap 4 with auth. So let's see both way.
```php
php artisan ui bootstrap --auth
```

### Install NPM
You also need to install npm and run it.
```php
npm install
```
Run NPM
```php
npm run dev
```
