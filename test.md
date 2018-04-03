# Laravel ToDo App

This is a simple ToDo app with multiple user support.

This is built on Laravel Framework 5.1. This was built for demonstrate purpose.

## Installation

Clone the repository-
```
git clone https://github.com/milon521/laravel-todo.git
```

Then cd into the folder with this command-
```
cd laravel-todo
```

Then do a composer install
```
composer install
```

Then create a environment file using this command-
```
copy .env.example .env
```

Then edit `.env` file with appropriate credential for your database server. Just edit these two parameter(`DB_USERNAME`, `DB_PASSWORD`).

Then create a database named `todos` and then do a database migration using this command-
```
php artisan migrate
```

At last generate application key, which will be used for password hashing, session and cookie encryption etc.
```
php artisan key:generate
```
