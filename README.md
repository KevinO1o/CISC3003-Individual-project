# CISC3003-Individual-project
The source code are tested, if the configuration of the error, 
please check the database configuration, such as database password, 
port number and operating environment.
Suggested running environment version: PHP8.3.4 MYSQL: 8.0.36

Configuration details
1. Import the sql file in the database folder into the database to create 
the database automatically.
2. Move the entire source code into the running directory
3. modify the database configuration. The default database password 
is 123456, if your database password is not 123456, 
please go to config/dbconfig.php file to modify the database password.
define("PASS","root");change to define("PASS","");
The front-end page is loaded by default. In the background access path, you can add /Admin to the background
    后台默认帐号：admin	
    后台默认密码：admin888
    
    前台默认帐号：test
    前台默认密码：test
The default password of the foreground can be reset through the 
background management. The New password is 123456

---------------------------------------------------------------------------------

Using XAMPP or WAMP on Windows:
If you are using XAMPP or WAMP in your local development environment,
 you can enable the GD library by following these steps:

1. Open the XAMPP or WAMP control panel. 2.
2. Find PHP Configuration or Extension Management in the menu. 3.
3. Find and check the GD library. 4.
4. Save your changes and restart your Apache server.
After completing these steps, re-run your code and the error should no longer occur.
