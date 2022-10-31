# n8n with Mariadb
Starts n8n with Mariadb as database.

Start
To start n8n with Mariadb simply start docker-compose by executing the following command in the current folder.

IMPORTANT: But before you do that change the default users and passwords in the .env file!
```
docker-compose up -d
```
To stop it execute:
```
docker-compose stop
```
Configuration
The default name of the database, user and password for Mariadb can be changed in the .env file in the current directory.
