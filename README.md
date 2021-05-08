# Basic services for lamp stack

## Includes:
`nginx:latest, php-fpm:7.4, phpmyadmin:latest, mysql:latest`

## Usage
After running `docker-compose up` command, you can get access to your local server
at **http://localhost** address. Local database and data will be saved into **.docker/mysql** folder. http://localhost:8080 - 
address to phpmyadmin service.

### Config

- server host - http://localhost
- database host - db:3306
- database name - dbname
- database user - dev
- database password - dev
- database root user&password - root