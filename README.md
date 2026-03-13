\# Cloud Native DevOps – Blue Green Deployment with Docker



This project demonstrates a \*\*Blue-Green deployment strategy using Docker containers\*\* to simulate zero-downtime application updates.



The system contains \*\*two versions of a web application\*\* running in separate container environments:



\- \*\*Version 1 – Blue Environment (Current Production)\*\*

\- \*\*Version 2 – Green Environment (New Release)\*\*



The deployment model allows a new version to be tested before switching traffic, ensuring \*\*safe releases with minimal risk and downtime\*\*.



\---



\# Project Architecture



The application uses a simple containerised architecture.



Client Browser

↓

Blue Environment (Docker Container – Version 1)

Green Environment (Docker Container – Version 2)



Both environments run independently and can be switched during deployment.



\---



\# Technologies Used



\- Docker

\- NGINX

\- HTML / CSS

\- GitHub

\- DevOps Deployment Strategy



\---



\# Project Structure



