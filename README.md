# LAMP in Docker
A ready-to-use LAMP stack in Docker to be able to dev. and test with Apache / MySQL / PHP

### Situation
You want to test or develop a PHP / Apache / MySQL software, but don't want to install a LAMP stack directly on your OS

### Task
Being able to deploy a LAMP stack, quickly, without having to worry about local dependencies, compatibility and other issues.

### Action
- Clone the repo and start the docker-compose.yml
```sh
docker-compose up
```

- Create a database

In phpMyAdmin
```sh
Default: http://127.0.0.1:1238
```

### Result
Use the folder "html" for your web service files

Files related to the MySQL will be saved in the folder "mySql"

### Note

### ToDo
