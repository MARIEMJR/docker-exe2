# docker-exe2
* faire un build d'image avec ce Dockerfile, l'image est nommée tomcat:v1

`docker build -t tomcat:v1 .`

`docker images`

`docker history tomcat:v1 `

* Faire un docker run pour creer un container a partir de l'image tomcat:v1, en background, avec le mapping de port 30200

  `docker run -d -p 30200:8080 tomcat:v1`
  
