# Pimcore V2 for Developers
## with docker-compose

Cool to upgrade existing (old) Pimcore Versions.

- docker must be installed
- cd into root
- run: docker-compose up


##### default credentials

* host: mysql
* username: pimcore
* passord: pimcore
* database: pimcore2
* port: 3306


**Build on:**

- PHP 5.4
- MySQL 

		/.db-data # contains the database (will be built on first start)   
    	/config # contains the docker-compose config files (mysql, php.ini)
    	
### If you wanna build it by yourself:

#### Requirements
- php composer

#### Process:
1. git clone git@github.com:pimcore/pimcore.git /mypimcore
2. cd /mypimcore
3. copy files from /config