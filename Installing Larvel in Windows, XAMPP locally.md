## Installing Larvel in Windows, XAMPP locally
1. Downloaded Larvel source zip file from the below link
https://codeload.github.com/laravel/laravel/zip/master

1. Extracted it to htdocs folder
1. Opened CMD from that folder
1. Run the command `composer install`
  > took some time, Composer downloaded 86~ dependencies
5. Add the below lines to the `php/php.ini` file
  `````php
  extension=php_openssl.dll
  extension=php_ftp.dll
  `````
  > Check if these lines exist before adding
6. Added the .env file
7. Open CMD from the larvel folder [Inside] and run the command `php artisan key:generate`
