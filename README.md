Project Name: Secure Application CA2 
A brief description of your project.

Branch Name: 
main Branch for Part 4 

Table of Contents: "Docker Setup" - using cheatsheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
Installation: 
Steps for the installation of the Docker container
 `Inline code block`
"Docker Setup"
`docker network create  myca_network_ker`
"Running a MySQL Docker Image"
`docker run -d --name db -e MYSQL_ROOT_PASSWORD=my-secret-password mysql:latest`
"Running phpMyAdmin on Docker Network"
`docker run -d --name phpmyadmin -p 8080:80 --network  myca_network_ker phpmyadmin/phpmyadmin`

Usage
Instructions on how to use the project.

Contributing
Instructions on how to contribute to the project.

License
This project is licensed under the MIT License - see the LICENSE file for details.main
# secure_app_CA2
