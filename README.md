
# PHP Stock Management System 

This is a minimalist application designed for inventory management. The application has been developed using **procedural PHP, JavaScript, Bootstrap, jQuery, Ajax and MySQL**. These technologies have been used effectively to create an intuitive and functional interface that allows users to manage their inventory efficiently.


## 🛠 Skills
Javascript, HTML, CSS, PHP, MySQL, JQuery, Ajax, Bootstrap, DataTables.


## Authors

- [@Pascual-Eburi](https://www.github.com/Pascual-Eburi)


## Features

- BRANDS
  - Add brands
  - Edit brands
  - Delete brands
- PRODUCT CATEGORIES
  - Add category
  - Edit category
  - Delete category
- PRODUCTS
  - Add product
  - Edit product
  - Delete product

- ORDERS
  - Add order
  - Edit order
  - Delete order
  - Print Orders

- REPORTS
    - Generate reports
    - Print and Save report to pdf

- USER ACCOUNT
    - Change Email
    - Change Password


## Installation

- **Server Setup**
Download and install an XAMPP, LAMPP or WAMP package depending on your operating system. These packages include Apache, MySQL and PHP, providing a complete environment for running PHP web applications locally. You can choose one of the following:

- XAMPP: https://www.apachefriends.org/index.html \
- WAMP: http://www.wampserver.com/en/ \
- LAMPP (Linux): https://www.apachefriends.org/index.html
Once the selected package is installed, start the local server. Generally, there is a control interface or a control panel where you can start and stop the Apache and MySQL services.

Clone the repository

```bash
  git clone https://github.com/Pascual-Eburi/php-stock-management-app.git
```

Copy the PHP project files to the local web server directory. In most cases, you will find a folder called **"htdocs" or "www"** in the installation of your chosen package. Place the project files inside that folder.

- **Database Setup**
Open your web browser and visit http://localhost/phpmyadmin. This will open the database administration interface, which is usually included in the packages mentioned above. In the phpMyAdmin interface, create a new database for your project.

Once the database is created, select the newly created database in the navigation panel.

Look for the **import** option in the phpMyAdmin interface and select the SQL file provided in the repository. Make sure to select the correct database from the drop down menu if there are multiple databases.

Click the **"Run" or "Import"** button to import the SQL file and create the necessary tables and structures in the database. Verify that the import was successful and that the tables were created correctly.

- **Database Conection Configuration**
Edit file _php_action/db_connect.php_
```php
$localhost = "127.0.0.1";
$username = YOUR_DATABASE_USERNAME;
$password = YOUR_DATABASE_USER_PASSWORD;
$dbname = YOUR_DATABASE_NAME;
```
    
## Run Locally

Make sure your local server is started. Generally, there is a control interface or control panel where you can start and stop **Apache and MySQL** services.

To run your project, put the relative or absolute path in the browser URL. For example, **_if you have placed the project files in a folder called "php-stock-management-app"_** inside the web server folder, you can access it via http://localhost/php-stock-management-app.




## Screenshots

![App Screenshot](https://github.com/Pascual-Eburi/php-stock-management-app/assets/89548196/44179333-210f-4bd8-bbce-169649a41154)
![App Screenshot](https://github.com/Pascual-Eburi/php-stock-management-app/assets/89548196/b89c1004-4dcd-4603-b648-d72ad3b45f7f)


## License

[MIT](https://choosealicense.com/licenses/mit/)

