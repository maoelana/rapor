<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Setting Rapor

- git clone https://github.com/maoelana/rapor.git
- cd rapor
- composer install --prefer-dist //membuat folder vendor
- cp .env.example .env
- sesuaikan konfigurasi database pada file .env dengan pengaturan di local
- buat database: rapor
- php artisan migrate
- npm install //membuat folder node_modules
- php artisan key:generate
- php artisan serve
- klik menu register untuk buat username password lalu login
