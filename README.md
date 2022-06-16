## This is the project of Nodejs application run with using persistance volume of redis and nginx for load balancer in between to web App ##

# Project structure
.
   ├── docker-compose.yml
   ├── redis 
   ├── nginx
   │   ├── Dockerfile
   │   └── nginx.conf
   ├── web1
   │   ├── Dockerfile
   │   ├── package.json
   │   └── server.js
   └── web2
       ├── Dockerfile
       ├── package.json
       └── server.js
