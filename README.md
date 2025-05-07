# Shinigami Bank — Online Banking System 

Welcome to Shinigami Bank, an online banking platform designed for secure, efficient user management, account summaries, money transfers, and notification management.

## Features

* User Login, Manager Login, and Cashier Login
* View account summaries
* Transfer funds between accounts
* View account statements
* Receive personalized notifications
* Contact the bank via a feedback form
* Secure session management
* Carousel for promotional images
* Responsive design with Bootstrap

## Project Structure

* index.php – Main dashboard after login (for users)
* login.php – Login page for User, Manager, and Cashier sessions
* assets/ – Contains autoloader, database connection (`db.php`), functions, CSS/JS files
* images/ – Logo, backgrounds, and carousel images

##  Built With

* PHP
* MySQL (XAMPP Server)
* Bootstrap 4 (for styling and responsiveness)
* HTML5 / CSS3

## ⚙️ Setup Instructions

1. Install **XAMPP** and start **Apache** and **MySQL**.
2. Clone or download this project into your XAMPP `htdocs` directory.
3. Create a database named `mybank` and import the SQL structure (not provided here).
4. Adjust database connection details if necessary in:

   ```php
   $con = new mysqli('localhost', 'root', '', 'mybank');
   ```
5. Start the server and visit:

   ```
   http://localhost/your-project-folder/login.php
   ```

## Default Login Credentials (for Testing)

|   Role  |                       Email                       |   Password  |
| :-----: | :-----------------------------------------------: | :---------: |
|   User  |     [some2@gmail.com](mailto:some2@gmail.com)     | tupilato123 |
| Manager | [manager@manager.com](mailto:manager@manager.com) | tupilato123 |
| Cashier |             (Add your cashier account)            | tupilato123 |

Note: You can modify users and credentials directly in the database.

## Security Notes

* Passwords are stored in plaintext (should be hashed in production).
* No CSRF protection (add for production).
* No input validation/sanitization (should use prepared statements).

## Author

Sumit Tamang
Presented as a project for Shinigami Bank.


