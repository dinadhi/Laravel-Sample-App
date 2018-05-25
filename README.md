# Sample APP
Laravel VueJS Sample App

##Summary for App
It's a Login and Profile Page Sample App. 
User can create a user via migrate command and then login using the username and password on profile page.
As soon as the user log's in, user can edit their profile name and password.
 
## Installation:
* Clone the repo
* Copy `.env.example` to `.env`
* Configure `.env`
* `cd` to the repo
* Run `composer install --no-scripts`
* Run `php artisan key:generate`
* Run `php artisan migrate --seed`. A user will be seeded so that you can login, where:
    * email is: `john@example.com`
    * password is: `peter`
* Run `npm install`
* Run `npm run watch`
* View the site by 
    * Either running `php artisan serve` if you are not using vagrant homestead or laravel valet (in a new terminal/command prompt)
    * Otherwise go to your local dev url configured in vagrant
