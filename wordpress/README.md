# Wordpress install for docker

## Config vars
MYSQL_ROOT_PASSWORD - set the password to be shared between the mysql and wordpres containers

## Volumes
### Wordpress container 
- /var/www/html - where the wordpress install is

### MySQL container 
- /var/lib/mysql - where the MySQL data is 

## How to run
```bash
fig up
```
