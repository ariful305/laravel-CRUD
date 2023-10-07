## Laravel CRUD
![App Screenshot](public\images\dashboard.png)

## Getting Started
To get started with this project, you will need to have the following software installed:

- PHP (version 8.0 or higher)
- Composer
- MySQL
Once you have installed these prerequisites, you can clone the project to your local machine:
```bash
git clone https://github.com/ariful305/laravel-CRUD.git
```
Next, navigate to the project directory and install the required dependencies:
```bash
cd laravel-CRUD
composer install
```
Create a new database for the project and configure the database connection in the .env file:
```bash
cp .env.example .env
php artisan key:generate
```
Then, run the database migrations:
``bash
php artisan migrate

You can then start the development server:
```bash
php artisan serve
```
