
Welcome to my Portfolio !

# Description
This repository is a 48 hours Symfony project cloturing the Wild Code School Bootcamp for Web and Mobile developers session (sept2022-febr 2023).
Students where expected to build or a website, or a porfolio from A to Z.

# Process and technical expectations :
Userstories
Wireframes
Github repository
Database designing
Necessary CRUD on the concerned entities

# Steps to launch the project on your computer
- Clone the repo from Github.
- Run "composer install".
- Run "yarn install" then "yarn watch"
- Create config/db.php from config/db.php.dist file and add your DB parameters.
define('APP_DB_HOST', 'your_db_host');
define('APP_DB_NAME', 'your_db_name');
define('APP_DB_USER', 'your_db_user_wich_is_not_root');
define('APP_DB_PASSWORD', 'your_db_password');

Import database.sql in your SQL server : you can do it manually or use the migration.php script which will import a database.sql file.
Run the command "symfony server:start" and go to your favorite browser.

Have fun!