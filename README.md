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



cloud-native-devops-blue-green-deployment

│

├── app-v1

│ ├── index.html

│ ├── styles.css

│ └── Dockerfile

│

├── app-v2

│ ├── index.html

│ ├── styles.css

│ └── Dockerfile

│

├── screenshots

│

└── README.md





\---



\# Running the Application



\### Build Version 1



docker build -t webapp-v1 ./app-v1

docker run -d -p 8081:80 webapp-v1



Access:http://localhost:8081/



\### Build Version 2

docker build -t webapp-v2 ./app-v2

docker run -d -p 8082:80 webapp-v2





Access:http://localhost:8082/







\---



\# Blue Green Deployment Concept



Blue-Green deployment is a release management strategy that reduces downtime and risk.



Blue = current production version  

Green = new version ready for release



Traffic can be switched from Blue to Green once the new environment is verified.



\---



\# DevOps Learning Outcome



This project demonstrates:



\- Containerisation of applications using Docker

\- Blue-Green deployment strategy

\- Versioned application environments

\- Git-based source control workflow







