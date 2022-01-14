## Laravel Social Login with google, facebook and github (Laravel Socialite)

## Clone this repo
```
https://github.com/carlospessin/laravel-social-login
```

## Install composer packages
```
$ cd laravel-social-login
$ composer install
```

## Create and setup .env file
```
$ copy .env.example .env
put database credentials in .env file
$ php artisan key:generate
```

## Create app for google, facebook and github
```
For google app
https://console.developers.google.com/
For facebook app
https://developers.facebook.com/apps/
For gitgub app
https://github.com/settings/developers

Put all ids and secrets in .env file
```

## Migrate and insert records
```
$ php artisan migrate
```
