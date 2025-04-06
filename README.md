# php-login-page
This project demonstrates a simple PHP login page connected to a localhost server and a MySQL database. It allows users to log in using credentials stored in the database, with basic authentication mechanisms in place.
Here is the sql code for teh data base tables creation:


CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL,
    password VARCHAR(255) NOT NULL
);
