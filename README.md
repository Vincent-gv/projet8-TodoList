# Todo & Co

### Project #8 - Application Developer Student - PHP / Symfony Openclassrooms

Improve an existing ToDo & Co Symfony application

## Application installation

### Minimum required

* Apache server 2.4.
* Version PHP 7. 

### Installation

* Clone the project in your local server environment with the command:
`` 
git clone https://github.com/Vincent-gv/Projet8-TodoList.git
`` 
* Run 
`` composer install 
``  at the root of the folder to install the dependencies.
* Create a local database and update environment variables in .env file.
* Run Doctrine to load SQL tables: 
`` 
php bin/console doctrine:database:create
`` 
 * Load fixtures into the database: 
`` 
 php bin/console doctrine:fixtures:load
`` 

## Developed with

* ** Symfony 5.1 **
* ** PHP 7.4.7 **
* ** Mysql **
* ** Composer **

## Author

** Vincent Gauchevertu ** - Openclassrooms student
https://github.com/Vincent-gv/

The project is hosted [online](https://todo.vincent-dev.com/).

## Project badges```

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/b9fcb8208a03424797c3d2b4a49562fb)](https://www.codacy.com/gh/Vincent-gv/projet8-TodoList/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Vincent-gv/projet8-TodoList&amp;utm_campaign=Badge_Grade)
[![Maintainability](https://api.codeclimate.com/v1/badges/2b78659c63a712b969bc/maintainability)](https://codeclimate.com/github/Vincent-gv/projet8-TodoList/maintainability)