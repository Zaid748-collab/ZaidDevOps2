# ZaidDevOps2 - In Progress
This project demonstrates a complete CI/CD pipeline for a Java application using Maven, GitHub Actions/Jenkins, and AWS EC2.
The application is built and packaged with Maven, automatically tested, and deployed to a configured EC2 instance.

The pipeline performs the following:

Code Integration: Every push triggers automated build and test steps using Maven.

Build Automation: Maven handles dependency management and produces a deployable .jar/.war artifact.

Continuous Deployment: The pipeline securely connects to an AWS EC2 server (via SSH) and deploys updated builds automatically.

Infrastructure: The EC2 instance is configured for secure access, running the Java service and hosting application updates.

This end-to-end workflow ensures fast, reliable, and repeatable delivery of changes from source code to a live EC2 environment.

This project is still in progress

If you want, I can expand it into a full README (installation steps, architecture diagram, commands, pipeline YAML, EC2 setup, etc.).
