---
1. What is Docker and why is it used?
2. Difference between Docker Container and Virtual Machines?
3. What is a Docker Image vs a Docker Container?
4. What is Docker Hub?
5. Explain the Docker architecture (Docker Engine, Daemon, CLI, Registry).
6. What is a Dockerfile and why do we use it?
7. Explain the difference between `docker run`, `docker start`, and `docker exec`.
8. How do you list running containers and images?
9. What is the difference between `docker ps` and `docker ps -a`?
10. Difference between `ENTRYPOINT` and `CMD`.
11. What is the difference between `COPY` and `ADD` in a Dockerfile?
12. How to pass environment variables into a container?
13. What happens if you don’t specify a tag when pulling an image?
14. How do you expose ports in Docker?
15. Difference between host, bridge, and none networks in Docker?
16. What happens when you map a container port to the host?
17. How do you check the IP address of a container?
18. What is Docker Compose and why is it used?
19. Difference between Docker Compose and Docker Swarm?
20. Explain a `docker-compose.yml` file.
21. How do you view container logs?
---
  common:
    What is Docker, and how does it differ from traditional virtualization?
    Explain the key components of Docker's architecture.
    What are Docker containers, and how do they work?
    How do you create a Docker image? Can you explain the Dockerfile and its significance?
    What is the difference between an image and a container in Docker?
    What is Docker Compose, and how does it simplify multi-container application orchestration?
    Describe the Docker networking modes and how containers communicate with each other.
    How do you manage data persistence in Docker containers?
    Explain the concept of Docker volumes and when you would use them.
    How do you secure Docker containers and images? Can you mention some best practices for container security?
    Explain the concept of multistage Dockerfile caching and how it impacts the build process.
    Entrypoint vs CMD?
    How to performance optimized lightweight Docker container?

  Scenario:
    Your Dockerized application relies on a database for persistence. Explain how you would manage data persistence and backups for the database in a containerized environment.
    Your team uses Docker Compose for local development, but you want to ensure that the production environment is consistent with the development environment. How would you achieve this consistency in both environments?
    Your organization is adopting a microservices architecture with multiple teams working on different services. How would you manage Docker image versioning and ensure smooth updates across all services while minimizing disruptions?
    Your Docker containerized application is experiencing a memory leak in production. Walk me through the steps you would take to diagnose and address the issue.
    Your team is concerned about security in the Docker environment. Describe the security best practices you would implement to safeguard against potential vulnerabilities and threats.
    You are migrating an existing application to a new host that has Docker installed. How would you transfer and deploy the application using Docker to minimize downtime and ensure a smooth transition?
    You have been tasked with implementing a blue-green deployment strategy for a Dockerized application. Explain the steps involved in this process and how it ensures minimal downtime during updates.
    You are responsible for monitoring a fleet of Docker containers in a production environment. What tools and practices would you use to monitor container health, resource usage, and performance?

    
