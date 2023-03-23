# Laravel Authentication Breeze with UI

## Laravel Installer Globally Setup
```
composer global require laravel/installer
```

## Install Laravel Project
```
laravel new project_name
```

## Install Laravel Breeze Authentication
```
composer require laravel/breeze --dev
php artisan breeze:install
```

## Install Laravel Kamona KUI
```
composer require kamona/kui-laravel-breeze --dev
php artisan kui-breeze:replace blade
```

## Migrate All The Tables
```
php artisan migrate
```

## Install All Packages
```
npm install
npm run dev
```