Execute Bash on server container
by running docker-compose exec server bash.

I’ve set our working directory on the server to /var/www/html.
While at it, run composer update. 

Now check http://localhost:8000/ and http://localhost:8080/. 
Your site and PhpMyAdmin should be available!