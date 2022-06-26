# docker-exe2
docker build -t tomcat:v1 .  
docker history <image>  #EXPOSE 8080  
docker inspect <image> #Ports 8080    
docker run -d --name mycontainer -p 20200:8080 tomcat:v1  
docker exec -it <container_ID> /bin/bash  
useradd -d /opt/tomcat -U -s /bin/false logwire  
passwd logwire  #docker
docker image tag tomcat:v1 <docker_hub_account>/tomcatImage  

#exercice3
git checkout -b exercice3  
docker-compose up 
