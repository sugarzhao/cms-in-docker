# CMS-in-docker
Using docker-compose to make solo running in docker with nginx, tomcat and mysql .

## how to use

* run "./build-image.sh" to pull mysql , nginx and tomcat image from hub.docker . 

* mv the war file into ./webapps   
    
* run "docker-compose up -d" to start up    

* connect to mysql and create schema named ofcms .

* open your browser , and visit http://localhost/ofcms-admin
    
* and you can find something like this :
    
                 
