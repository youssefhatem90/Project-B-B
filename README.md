## Jenkins/Java/Artifactory/Docker/Docker-compose/Selenium integration 

This Project show how to connect between a java project in jenkins and Artifactory ( Repository Manager ) and SonarQube ( Code Quality ) also Docker/Docker-Compose  and Selenium 
   
Configured Jobs 

1. Simple Java app with Maven ( Building profile)
2. Java Artifactory integration 
3. java Docker integration 
4. Java SonarQube integration 


# Jenkins 
- port 8080
- username: devops
- password: devops 


# Artifactory
- port: 9090
- username: admin
- password: password 


# SonarQube
-port: 9000


# Docker 
--> please check the docker-compose file "docker socket is mounted between host and container"

# Selenium: 

docker-compose file 
