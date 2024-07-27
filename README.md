# MongoDB Docker Compose Setup

This repository contains a Docker Compose configuration for setting up a MongoDB container.

## RUN Docker Compose
docker-compose up -d


**Checking Docker Network**
To check the existing Docker networks, use the following command:

docker network ls

This will list all Docker networks, including app-network.

**Running the Project**
To run a project that connects to the MongoDB container, use the following command:

docker run -d --name container_name --network app-network -p 8080:8080 --restart always <image:latest>
Replace <image:latest> with the appropriate Docker image name for your project.

Notes
Make sure Docker and Docker Compose are installed and running on your system.
Ensure the MongoDB service is running before starting your project container.
For further details on configuring MongoDB or Docker, refer to their respective documentation.


Feel free to adjust the details or add any additional information relevant to your setup!


