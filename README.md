# This is an Imgur clone started since they began showing adverts on image upload

## Installation

- Create a database

- Execute:
```
git clone https://github.com/keymetaphore/laravel-image-uploader
composer install
cp .env.example .env
```
- Configure .env file with the correct database credentials
- Execute:
```
php artisan key:generate
php artisan migrate
php artisan storage:link
```

# Warning
At this stage, this project is not ready for production use
