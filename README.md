## Laravel Socialite (Social Login) - Login with google, facebook and github

## Clone this repo
```

```

## Install composer packages
```
$ cd whatsappCheckout
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
