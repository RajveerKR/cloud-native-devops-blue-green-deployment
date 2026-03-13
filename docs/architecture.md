\# System Architecture



This project demonstrates a simple \*\*Blue-Green deployment architecture\*\* using Docker containers.



\## Components



1\. \*\*Client Browser\*\*

&#x20;  - Users access the web application through a browser.



2\. \*\*Blue Environment\*\*

&#x20;  - Running Version 1 of the application.

&#x20;  - Represents the current production version.



3\. \*\*Green Environment\*\*

&#x20;  - Running Version 2 of the application.

&#x20;  - Used to deploy new features safely.



4\. \*\*Docker Containers\*\*

&#x20;  - Both environments run inside Docker containers for portability and isolation.



\## Deployment Strategy



Blue-Green deployment ensures zero downtime by allowing a new application version to run in parallel with the existing production environment before switching traffic.

