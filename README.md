# Magento

## Setup
Copy mysql.env.example file to mysql.env, remember to change mysql password 

Run bin/up 

## Available commands
    bin/down
        remove all containers
    
    bin/list
        list all images
    
    bin/mysql
        start mysql container
    
    bin/start
        start all containers
    
    bin/status
        list containers status
    
    bin/stop
        stop all containers
    
    bin/up
        create containers
    

## Links
### Magento 2.4 Developer Documentation
https://devdocs.magento.com/?_ga=2.104660931.237812297.1601263100-1419148679.1601263100

### Requirements
https://devdocs.magento.com/guides/v2.4/install-gde/system-requirements-tech.html
 
#### PHP requirements
https://devdocs.magento.com/guides/v2.4/install-gde/prereq/php-settings.html 

### TODO
done: nginx 1.x
 
done: MySQL 8.0
 
: PHP 7.4
 
: PHP extensions
  ext-bcmath, ext-ctype, ext-curl, ext-dom, ext-gd, ext-hash, ext-iconv
  ext-intl, ext-mbstring, ext-openssl, ext-pdo_mysql, ext-simplexml, ext-soap
  ext-xsl, ext-zip

: PHP OPcache
 
: PHP settings

: Elasticsearch 7.6.x
