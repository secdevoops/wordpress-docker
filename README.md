# wordpress-docker
A simple docker compose file configured to start up a wordpress with mysql and phpmyadmin


# 1.- Configuration
Modify database user/password and root password.

Volumnes will be created under 

    ./secdevoops_wordpress/ with all wordpress content
    
    ./secdevoops_db/ to keep all mysql data

# 2.- Run the application
docker-compose up

# 3.- Enjoy
Wordpress is available on http://localhost
Phpmyadmin is available on http://localhost:8000
