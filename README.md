# Wordpress-Blog

Simple WordPress blog using docker-compose.
Prerequisite To launch WordPress site with database using docker-compose on Centos-7.

Step 1: Install docker
# yum install docker

Step 2: Install docker-compose
# sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose.

Step 3: To assign execute permission to docker-compose file.
	# sudo chmod +x /usr/local/bin/docker-compose

Step 4: Now create “docker-compose.yml” file:
	# vim docker-compose.yml

Step 5: Now put following code in your “docker-compose.yml” file

Step 6: Now to run yml file use:
	# docker-compose up -d

Step 7: Now your both containers are up with above mentioned configuration.
Go to browser type localhost:5000
