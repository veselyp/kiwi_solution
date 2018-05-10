# kiwi_solution
Nginx container with simple site. Serves as solution to entry task for the Kiwi.com Weekend in the Cloud.

# Using the container
Use Docker itself:

  `docker run --detach --rm=true --volumes ./wwwroot/:/var/www/ --name=nginx --hostname=nginx nginx-simple`

Or use Docker-compose:

  `docker-compose up -d`