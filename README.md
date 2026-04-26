Project: YouTube Clone Deployment on Azure with CI/CD Pipeline

Designed and deployed a scalable YouTube clone web application using Azure Web App (Linux), implementing a complete CI/CD pipeline with Azure DevOps to automate build and deployment processes.

Developed a multi-stage YAML pipeline that triggers on code changes in the main branch, performing automated Node.js dependency installation, application build, and artifact publishing. Configured the deployment stage to download build artifacts and deploy them to Azure Web App using Azure Resource Manager (ARM) service connection.

Leveraged NPM tasks for build automation and implemented artifact management for consistent and reliable deployments. Enabled continuous integration and continuous delivery (CI/CD) to reduce manual effort and ensure faster, repeatable releases.

Key Highlights:

Automated end-to-end CI/CD pipeline using Azure DevOps YAML
Hosted application on Azure Web App (Linux environment)
Implemented artifact publishing and deployment using pipeline stages (Build & Deploy)
Integrated Node.js build process using NPM
Used OneDeploy method for efficient application deployment
