<p align="center">
    <img src="https://user-images.githubusercontent.com/807318/27274054-b06652c6-54c9-11e7-83ab-f4a3fa6109b7.jpeg" alt="Laravel Nigeria meetup">
</p>
<p align="center">Source code of the Laravel Nigeria meetup website. Developed &amp; Designed by <a href="https://creativitykills.co" target="_blank">CreativityKills Co.</a></p>
<p align="center"><a href="license.txt"><img alt="GitHub license" src="https://img.shields.io/github/license/laravelnigeria/website.svg"></a></p>


<p>&nbsp;</p>
<p>&nbsp;</p>

## Requirements
Requirements goes here
* Twitter application and credentials, also set the env variables
* Mailgun or any other mail driver
* Set up the required ENV variables (list them)

<p>&nbsp;</p>

## Installation
- fork & clone

        git clone git@github.com:laravelnigeria/website.git my-directory
 
- cd to your new directory and install dependencies

        cd my-directory
        composer install

<p>&nbsp;</p>

## Configuration
- make a copy of the .env.example file or just rename it to .env
- generate a new key

        php artisan key:generate
        
- set up your database
        
        DB_CONNECTION=
        DB_HOST=
        DB_PORT=
        DB_DATABASE=
        DB_USERNAME=
        DB_PASSWORD=
        
- set the following vars https://secure.meetup.com/meetup_api/key/

        MEETUP_URL_NAME=laravel-nigeria
        MEETUP_KEY=

- create a twitter app and set the following vars https://apps.twitter.com/
    
        TWITTER_CONSUMER_KEY=
        TWITTER_CONSUMER_SECRET=
        TWITTER_ACCESS_TOKEN=
        TWITTER_ACCESS_TOKEN_SECRET=
        TWITTER_SEARCH_QUERY="#laravel -filter:retweets -filter:replies"

- run the migrations

        php artisan migrate

- seed the database

        php artisan db:seed
        
<p>&nbsp;</p>

## Todos
- [x] Contact us popup
- [x] All talks page
- [x] Bug in the slider getting big momentarily
- [ ] Contribute page
- [ ] Jobs page
- [ ] Use web intents to add retweet, reply and like buttons to the tweet section
- [ ] Create custom error pages
- [ ] Create error pages for the custom exceptions e.g `ApiCommunicationException`.
- [ ] Create a new Twitter application for the Laravel Nigeria application
- [ ] Meetup feedback popup with link to leave reviews
- [ ] Learning track availability alert form
- [ ] Learning track

<p>&nbsp;</p>

## Contributing
Contribution instructions goes here