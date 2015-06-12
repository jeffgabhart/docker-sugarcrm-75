docker-sugarcrm-75
===================

Dockerfile for Apache &amp; PHP 5.4 for SugarCRM.

Docker Compose for SugarCRM, MySql, and ElasticSearch.

## Instructions

### Download Sugar Pro 7.5.2.1

### Extract to

    /var/www/SugarPro-Full-7.5.2.1

### Update file permissions

    chmod -R 777 /var/www/SugarPro-Full-7.5.2.1

### Add to /etc/hosts

    127.0.0.1 sugar.dev

### Two ways to run the containers.

#### Run with container output shown in terminal

##### Start

    docker-compose up
    
##### Stop

    Ctrl+c

#### Run as a daemon

##### Start

    docker-compose up -d

##### Stop

    docker-compose stop
