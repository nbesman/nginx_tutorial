# nginx_tutorial

Creating load balancer with "nginx" ahd "docker"
1. app1.py and app2.py - 2 (almost) identical tiny applications wrriten in python FLASK.  
2. nginx.config - routes the incomig trrafic, in a 4:6 ratio between app1 and app2. 
3. app1.py, app2.py and nginx.config are packed into Dockerfiles. 
4. docker-compose.yaml - building the containers for app1, app2 and nginx. after the containers are built, docker-compose will run and orchestrate the containers.



