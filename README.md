# php-secured-login-with-sql-injection-prevention
This code has a secured login via PHP and SQL and prevents SQL Injection of any level
This code has basic CSS for beautifying the page and has a PHP function called mysqli-real_escape_string() which takes in two parameters:
1. Your database connection variable (Like $conn, $con etc)
2. The string you want to remove hases from

Then it connects to a database named test (in XAMPP) and table named users_tutorial. You can change the names of these variables into
anything you like as long as the database and tables are present in the table.

You have to use XAMPP since I wrote it in accordance with it. But if you are using WAMPP just change the $hostname, $username, $password
fields.

Thank You
