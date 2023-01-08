# Installing Zabbix with docker-compose
This will deploy Zabbix installation with Docker, we will use a docker-compose.yml file to configure Zabbix:
* The Zabbix server
* The database (MariaDB)
* The web interface
* A monitoring agent for Zabbix server
  
 env_vars should be edited before deployment. At a minimum, edit the .MYSQL_PASSWORD and .MYSQL_ROOT_PASSWORD files, change to a personalized password.
