MyApp Extended
Welcome to the extended version of MyApp! This repository includes the implementation of CI/CD pipelines and Dockerized applications for independent components developed in Go, Next.js (TypeScript), and WordPress. Each component has its dedicated CI/CD pipeline to ensure quality, efficiency, and adherence to coding standards.

Components
Go Application: A component developed in Go language.
Next.js (TypeScript) Application: A component developed using Next.js framework with TypeScript.
WordPress Site: A component developed using PHP and WordPress.

Features Implemented
Version Control
Created a public GitHub repository with directories for each component.
Initialized repositories for the Go, Next.js, and WordPress components.
Continuous Integration
Implemented CI workflows for Go, Next.js (TypeScript), and WordPress components.
Configured pipelines to trigger on pushes to respective branches.
Integrated linting and unit testing for each technology.
Ensured CI pipelines fail if coding standards or tests are not met.

Containerization
Dockerized the Go application, Next.js (TypeScript) application, and WordPress site.
Created Dockerfiles for each application.
Pushed Docker images to a container registry (e.g., Docker Hub, AWS ECR).
Coding Standards Enforcement
Implemented PHPCS for the WordPress component to enforce WordPress coding standards.
Configured PHPCS checks into the CI pipeline for the WordPress component.
Implemented GolangCI-Lint for the Go application to enforce coding standards.
Configured GolangCI-Lint checks into the CI pipeline for the Go component.
Implemented ESLint and Prettier for the Next.js (TypeScript) application to enforce coding standards.
Configured ESLint and Prettier checks into the CI pipeline for the Next.js (TypeScript) component.

Orchestration
Updated the Docker Compose file to include services for Go, Next.js, and WordPress.
Ensured the Compose file can be used to spin up the entire extended application stack locally.

Continuous Deployment
Extended the CI/CD pipelines to include deployment stages for the Go, Next.js, and WordPress components.
Set up automatic docker image creation and pushed it on my dockerhub.

Documentation
Updated the README.md file with instructions on setting up and running the extended application locally.
Documented any changes made to the existing documentation based on the additional technologies.

Additional Notes
During the implementation, challenges were encountered in configuring linting and testing tools specific to each technology stack. However, thorough research and experimentation led to successful integration.
Choices were made to utilize widely adopted tools and practices for coding standards enforcement to ensure maintainability and compatibility across the development ecosystem.
For further details, refer to the individual component directories and documentation within the repository.

We hope you enjoy exploring MyApp-Extended! If you have any questions or feedback, feel free to reach out.