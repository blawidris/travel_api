# Travels & Tour API

This readme provides instructions on setting up and running the Travels and Tours API built with Laravel.

*Requirements:*

- PHP >= 7.4
- Composer
- MySQL database
- Git

*Installation:*

1. Clone the repository to your local machine:

```
git clone https://github.com/blawidris/travel_api.git
```

2. Navigate to the project directory:

```
cd travel_api
```

3. Install Composer dependencies:

```
composer install
```
4. Create a .env file by copying the .env.example file
5. Generate the application key:
```
php artisan key:generate

```
6. Migrate the database:
```
php artisan migrate

```
7. Start the development server:
```
php artisan serve

```