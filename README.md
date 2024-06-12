Prerequisites
PHP 7.4+
Composer
MySQL
Node JS
Installation
Extract the project
cd extacted_project_dir_name
Open up the terminal / bash and run composer install
Run cp .env.example .env or simply rename the .env.example file into .env
Create a database in mysql and change database connection credentials (host name, database name, user-name, password) in .env file according to your local mysql settings
Run php artisan migrate --seed to migrate all migrations and seed default admin and users data. If anything goes wrong, then re-check the .env file and confirm all of mysql settings are correct.
Run npm install to install JavaScript related dependencies
Run npm run dev to compile js, vue, scss files
Run php artisan serve to serve the project locally
Open up a browser and go to localhost:8000 to access the application front-end
