# My CodeIgniter Project

## Overview

This project is a web application built with CodeIgniter 4. It includes functionality for user registration, login, and session management. Users are redirected to a welcome page after successful registration or login.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   
cd your-repo-name

composer install

# .env file
database.default.hostname = localhost
database.default.database = database name
database.default.username = root
database.default.password = password
database.default.DBDriver = MySQLi

php spark migrate

php spark serve


