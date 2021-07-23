# SCA-Cloud-School-Application
Application for She Code Africa Cloud School, Cohort 2.
# Exercise 2 solution
* Clone this repository to your local machine using `git clone https://github.com/OyinOlamide/SCA-Cloud-School-Application.git`
* cd into the repository.
* Checkout to the branch start from master branch using `git checkout start`
* Cd into docker with `cd docker`
* Built the docker image from the Dockerfile using: `docker build -t oyinola/she-code-africa-cloud-school-application .`
* Ran the image on Docker using: `sudo docker run -p 5005:3030 -d oyinola/she-code-africa-cloud-school-application:latest`
* Pushed the image into Dockerhub using: `docker push oyinola/she-code-africa-cloud-school-application:latest`


* PS: Made a little mistake so updated `this is THE first assessment` to `this is MY first assessment`

# DOCKERHUB LINK
https://hub.docker.com/r/oyinola/she-code-africa-cloud-school-application
