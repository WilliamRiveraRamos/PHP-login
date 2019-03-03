# PHP-login
A login App with SESSIONS, Password hash, and Password recovery made with PHP 7, MySQL, phpMyAdmin, and Bootstrap.

How to use it?

1. Open XAMPP dashboard.
2. Click phpMyAdmin on the menu.
3. Create a new database "phplogin".
4. Create table "users" with 4 fields*:

    Id - mediumint, Primary Key, AUTO_INCREMENT
    
    Name - varchar
    
    Email - varchar
    
    Password - varchar(128)
    
*See screenshoot name table-users-Capture.jpg

5. Download or clone this repo.
6. Put "PHP-login" folder inside your "xampp" folder.
7. Open your browser and type "localhost:8080/PHPLogin"
8. Enter the account info and press "Create my account" button.
9. Check if the info. is correct on the database and if the password is a hash.
10. Go back to your browser and click "Login"
11. Enter the email and password you use when created your account and click login.
12. If everything is ok, you are logedin and a SESSION for 1 minute is created.
