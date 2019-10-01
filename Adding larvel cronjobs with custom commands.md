## Adding larvel cronjobs with custom command
Referred website : https://www.sitepoint.com/managing-cronjobs-with-laravel/
> The website is based on a older version of Larvel

Cache link : https://web.archive.org/web/20170705081347/https://www.sitepoint.com/managing-cronjobs-with-laravel/
### :warning: Changes from the referred website
To start the Laravel Scheduler, the command used `* * * * * php /path/to/artisan schedule:run 1>> /dev/null 2>&1` will not work in Windows OS devices.
