<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# How to Clone Larvel Project

- Open u Terminal, and type
```
git clone /*repo ini*/
```
- enter dir and open codeitor
```
cd /*nama folder hasil repo*/
code .
```
- Install Composer in this Project
```
composer install
```
- Copy file .env.exemple sekaligus ubah nama to .env
```
cp .env.example .env
```
- Generate key_app nya
```
php artisan key:generate
```

- Buat DB-nya di [phpmyadmin](http://localhost/phpmyadmin/) dengan nama db <strong>live_coding</strong>

- Jalankan dulu PHP migrate nya dengan perintah

```
php artisan migrate --seed
```

- Start u Project

```
php artisan serve
```

