# CI-CD-Pipeline-with-GitHub-Actions-and-AWS
CI/CD Pipeline with GitHub Actions and AWS and Notification will be on Slack

Solution Overview
1. GitHub Actions: Workflow Orchestration tool that will host the Pipeline.
2. IAM OIDC identity provider: Federated authentication service to establish trust
between GitHub and AWS to allow GitHub Actions to deploy on AWS without
maintaining AWS Secrets and credentials
3. Amazon S3: Amazon S3 to store the deployment artifacts.
4. AWS Elastic Beanstalk: AWS Elastic Beanstalk is an easy-to-use service for deploying
and scaling web applications and services developed with Java, .NET, PHP, Node.js,
Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and
IIS.
5. Slack: Setting Up Slack Notification after All check are passed or Failed CI/CD
Process.

Prerequisites
• An AWS account with permissions to create the necessary resources.
• A Git Client clone the provided source code. In our case we are using creating a
fork from following link ( https://github.com/alexnm/react-ssr ). A baseline for
server-side rendering React application
• A GitHub Account with permissions to configure GitHub repositories, create
workflows, and configure GitHub secrets.
• A Slack Account with permissions to configure Slack Notification with help of
Slack webhook.

For more details on deployment you can see Documentaion of this,it is in Repo File name :CICD_GITACTIONS_ON_AWS_BY_PUNIT_KUMAR
