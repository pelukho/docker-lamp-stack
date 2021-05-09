# Basic services for lamp stack with blackfire profiler

## Includes:
`nginx:latest, php-fpm:7.4, phpmyadmin:latest, mysql:latest, blackfire:latest`

## Blackfire
For using blackfire profiler you must register on https://blackfire.io and you have to install extension for browsers https://blackfire.io/docs/integrations/browsers/chrome

## Usage
After running `docker-compose --env-file .env.local up` command, you can get access to your local server
at **http://localhost** address. Local database and data will be saved into **.docker/mysql** folder. http://localhost:8080 - 
address to phpmyadmin service. Press on extension of blackfire to start profiling.

## !Importent...

In local .env file must be placed variables for blackfire, from profile page and this file must not be in VSC

### Config

- server host - http://localhost
- database host - db:3306
- database name - dbname
- database user - dev
- database password - dev
- database root user&password - root