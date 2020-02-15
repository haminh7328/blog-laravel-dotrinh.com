# A Tiny Laravel Blog
A tiny blog base on Laravel. It's for educate. You shouldn't use for your product.

## Install for development
- git clone -b develop https://github.com/haminh7328/blog-laravel-dotrinh.com.git
- vagrant plugin install vagrant-vbguest
- vagrant plugin install vagrant-hostsupdater
- vagrant box add laravel/homestead
- cd blog-laravel-dotrinh.com/Homestead
- vagrant up
- vagrant ssh
- cp .env.example .env
- Open .env file in IDE and set connection to database
- DB_CONNECTION=mysql
- DB_HOST=127.0.0.1
- DB_PORT=3306
- DB_DATABASE=laravel-dotrinh
- DB_USERNAME=root
- DB_PASSWORD=root
- composer install
- php artisan key:generate
- Go to: http://192.168.10.10
- Done!