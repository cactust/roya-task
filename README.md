## Installation
Get a clone from this repository, you have to do the following:
- go to the file from your terminal and run the following command
```bash
composer install
```
- Create an empty database.
- Rename .env.example file to .env
- Set the database connection from .env file
- Generate a project key
```bash
php artisan key:generate
```
- Run the migration file
```bash
php artisan migrate
```
- Run the seeder file to add roles and admin user(important)
```bash
php artisan db:seed
```
- Start the development server with default option
```bash
php artisan serve
```
- Log in as an admin
Email: info@roya.tv and Password: Hello124