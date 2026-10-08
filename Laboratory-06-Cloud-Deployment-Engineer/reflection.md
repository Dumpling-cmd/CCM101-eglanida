# Mission Reflection

**Name:** Edmund Glanida

**Course and Section:** BSIT 4-L

Using a Docker Compose YAML file makes the deployment job easier because I can define the entire multi-container application in one configuration file. Instead of manually entering many Docker commands for each container, I can use one Compose command to create and start the services. This also makes the deployment easier to repeat because the configuration is already written in the YAML file.

YAML indentation is very important because YAML uses indentation to determine the structure of the configuration. If the indentation is incorrect or tabs are used instead of spaces, Docker Compose may not understand the file correctly and can return an error. This can prevent the services from starting successfully.

Environment variables such as `MYSQL_PASSWORD` are used to provide configuration values to the containers. In this activity, the variables allow the Nextcloud application and MariaDB database to use the required database credentials and settings. Using environment variables also keeps configuration values organized within the Compose file.

I felt that deploying Nextcloud in only a few minutes was convenient and interesting. Docker Compose made it possible to start both the Nextcloud application and MariaDB database without manually configuring each container separately. Seeing the Nextcloud setup page in the browser also helped me understand how the containers work together.

Since Mission 1, my understanding of cloud computing has developed from learning basic cloud concepts to gaining more practical experience with containers, storage, and multi-tier applications. I now understand better how different services can work together as part of a cloud-based system. This laboratory also improved my confidence in using Linux commands, Docker, and configuration files for deployment.