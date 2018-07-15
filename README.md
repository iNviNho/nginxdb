# NginxDB

Simple Nginx and DB setup using 2 separate commands to deploy them

# Nginx

To start nginx for master run **./deploy-nginx-master.sh**  
To start nginx for production run **./deploy-nginx-production.sh**

# DB

To start database run **./deploy-database.sh**

Hints 

- Do not forget to change your password or disable access to DB from outside.
- If you want containers to communicate between each other do not forget to set correct
network to join