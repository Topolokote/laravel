## About Project
This project represents the way to run "1" or "100000" Http requests by a php artisan command.

## Artisan Command Line
The created command line to run the code is : "php artisan request:fake {processOption}" where the argument represents the option to run 1 or 100000 HTTP requests, if the processOption is "4" it will execute just one request, if the processOption is "5" it will execute 100000 requests in async way, if the processOption is missing or it is with another value than 4 or 5, it will display a message indicating to type the argumente to run command action.

## Artisan Command File
The command file is located in app\Console\Commands\RequestFakePost.php

