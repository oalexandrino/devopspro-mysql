docker run --name meu_mysql_local -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -e MYSQL_ROOT_PASSWORD=root_pwd -d -p 3306:3306 mysql
