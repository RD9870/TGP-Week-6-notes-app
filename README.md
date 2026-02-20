<p align="center"><a href="#" target="_blank"><img width="700" height="350" alt="NOTES APP" src="https://github.com/user-attachments/assets/fad8d72a-7acc-4b63-8bb3-acc14ebe4b7b" />
</a></p>

## 📝 Overview
This is a simple notes app API that allows users to add tasks and subtasks as well as writing comments on the tasks.

![Static Badge](https://img.shields.io/badge/-laravel-FF2D20?style=plastic&logo=laravel&labelColor=5b5b5b)
![Static Badge](https://img.shields.io/badge/-PHP-777BB4?style=plastic&logo=php&labelColor=5b5b5b)

## 🔓 Getting Started

1. Clone the repo to your local device and open the project folder in your IDE. 

```bash
git clone https://github.com/RD9870/TGP-Week-6-notes-app.git
```

2. Install all the needed packages and dependencies.

```bash
composer install
```

3. Create a .env file with the following template.

```bash
APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost

APP_LOCALE=en
APP_FALLBACK_LOCALE=en
APP_FAKER_LOCALE=en_US

APP_MAINTENANCE_DRIVER=file
# APP_MAINTENANCE_STORE=database

# PHP_CLI_SERVER_WORKERS=4

BCRYPT_ROUNDS=12

LOG_CHANNEL=stack
LOG_STACK=single
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=sqlite //change this to mySQL
//uncomment the lines below
# DB_HOST=127.0.0.1 
# DB_PORT=3306
# DB_DATABASE=laravel //create a local database and change this to its name
# DB_USERNAME=root //change this to your username
# DB_PASSWORD= //change this to your password or leave it empty if you don't have one

SESSION_DRIVER=database
SESSION_LIFETIME=120
SESSION_ENCRYPT=false
SESSION_PATH=/
SESSION_DOMAIN=null

BROADCAST_CONNECTION=log
FILESYSTEM_DISK=local
QUEUE_CONNECTION=database

CACHE_STORE=database
# CACHE_PREFIX=

MEMCACHED_HOST=127.0.0.1

REDIS_CLIENT=phpredis
REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=log
MAIL_SCHEME=null
MAIL_HOST=127.0.0.1
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

VITE_APP_NAME="${APP_NAME}"
```

4. Generate the key.

```bash
php artisan key:generate
```

5. Log in to the MySQL server:

```bash
mysql -u <username> -p
```

6. Create a MySQL database.

```bash

CREATE DATABASE <database_name>;
```

7. Create the tables in the database.

```bash
php artisan migrate
```

8. Populate the database

```bash
php artisan db:seed
```

9. Start the server locally

```bash
php artisan serve
```
