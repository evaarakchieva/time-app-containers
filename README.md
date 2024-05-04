# Time App containerization 

Time application consists of frontend written using Vue.js framework, 
backend written using Node.js and MySQL database.

There are Dockerfiles that create customed images for api and frontend services. 

File docker-compose.yaml runs containers from images created by Dockerfiles, MySQL 
and Adminer containers from official images.

I used port mapping, creation of volumes and dependencies specification.
