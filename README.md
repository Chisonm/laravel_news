# Laravel news Api
Built with Laravel and Laravel Sail

NOTE: Please Make sure your Docker is up and running before you run this project.

1. clone the repo `git clone https://github.com/Chisonm/laravel_news.git`
2. cd into the project project folder
3. run `php artisan sail:install`
4. To install the dependencies run `composer install`
5. Run the server `./vendor/bin/sail up`
6. Migrate the database `./vendor/bin/sail artisan migrate`
7. To run the recurring job running once a day to reset post upvote `./vendor/bin/sail artisan schedule:run`


Postman Collection Link: https://go.postman.co/workspace/Team-Workspace~c88b936a-59e6-45b2-86d2-212ca8ec5440/collection/10180177-4ea64965-e1f0-4d42-8b30-c7821937b0a8?action=share&creator=10180177

Deployment Link:http://laravel-news.danielchisom.me/api
