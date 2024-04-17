**MyApp** 

This repository includes the implementation of CI/CD pipelines and Dockerized applications for independent components developed in Go, Next.js (TypeScript), and WordPress. Each component has its dedicated CI/CD pipeline to ensure quality, efficiency, and adherence to coding standards.

**Components**

**Go Application:** A component developed in Go language.
**Next.js (TypeScript) Application:** A component developed using Next.js framework with TypeScript.
**WordPress Site:** A component developed using PHP and WordPress.

**Features Implemented**

**Version Control**

Created a public GitHub repository with directories for each component.
Initialized repositories for the Go, Next.js, and WordPress components.
Continuous Integration
Implemented CI workflows for Go, Next.js (TypeScript), and WordPress components.
Configured pipelines to trigger on pushes to respective branches.

**Containerization**

Dockerized the Go application, Next.js (TypeScript) application, and WordPress site.
Created Dockerfiles for each application.
Pushed Docker images to a container registry **Dockerhub**.

**Orchestration**

Updated the Docker Compose file to include services for Go, Next.js, and WordPress.

**Continuous Deployment**

Extended the CI/CD pipelines to include deployment stages for the Go, Next.js, and WordPress components.
Set up automatic docker image creation and pushed it on my dockerhub.
