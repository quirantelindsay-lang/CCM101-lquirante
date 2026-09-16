# Docker Container Lifecycle Management

Below are the commands executed to manage the Nginx container lifecycle:

*   **`docker ps`**: Lists all currently running containers so you can view their status, active ports, and specific Container IDs.
*   **`docker stop <container_id>`**: Gracefully halts the running container process without deleting its configuration or image.
*   **`docker ps -a`**: Displays all containers, including those that have been stopped or exited, verifying that the previous container is no longer active.
*   **`docker rm <container_id>`**: Completely removes the stopped container to clean up the environment and free up system resources.
