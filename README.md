# kiwi_solution
Nginx container with simple site. Serves as solution to entry task for the Kiwi.com Weekend in the Cloud.

# Running
Using Docker:

  `docker build -t kiwi_solution .`
  
  `docker run -itd --name mycontainer --publish 8080:80 kiwi_solution`
  