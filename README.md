# Slim Framework 3 Sample Application 
##### For developing in a docker PHP container using the
##### [php-composer](https://cloud.docker.com/u/localgyros/repository/docker/localgyros/php-composer/general) docker image.



## Run the Application

Run this command from the directory in which you have cloned this repo. This assumes a linux host!

    env UID=$(id -u) GID=$(id -g) docker-compose up

Please read [Speeding Up PHP with OPcache in Docker](https://laravel-news.com/php-opcache-docker?utm_medium=email&utm_campaign=Laravel%20Accountant%20Package%20MyCLI%20development%20on%20an%20iPad%20and%20More%20%20238&utm_content=Laravel%20Accountant%20Package%20MyCLI%20development%20on%20an%20iPad%20and%20More%20%20238+CID_908539c5fa96e64905a6b7e123741d6a&utm_source=email%20marketing&utm_term=Speeding%20Up%20PHP%20with%20OPcache%20in%20Docker) for more information about setting specific OPcache related ENV vars
in the `docker-compose.yml` file.
