# temp_docker
Build the Docker Image
To build the Docker image, use the following command:
docker build -t project-name:tag .
Run the Docker Container
To run the Docker container, use the following command:
docker run -d -p 8080:80 project-name:tag
Replace project-name and tag with the same values used during image building.
This example assumes your application listens on port 80 inside the container.
Access the Application
Once the Docker container is running, you can access your application in a web browser by navigating to http://localhost:8080 or the appropriate URL.
