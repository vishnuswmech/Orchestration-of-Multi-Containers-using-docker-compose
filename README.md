# docker-compose
Technologies used : Docker-compose on top of Redhat Linux 8 (RHEL 8)

Matomo is a free and open-source web analytics application which is used to track online visits to one or more websites and displays reports on these visits for analysis. 

In this project, Matomo which uses MySQL as its database server is deployed in docker with the help of Docker-Compose.

Post Address Translation (PAT) is also included in this project for outside accessibility.

Persistent volume named mysql_storage is used as a Matomo's database for permanent storage.
