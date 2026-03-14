### CI/CD Pipeline using CodePipeline, ECS & ECR

- Key Tasks
  - Build and push a Docker image of the website to Amazon ECR
  - Setting up a CodePipeline to automate the build and deploy process.
  - Deploy the Dockerize game to Amazon ECS using a Fargate launch type

- Services Used
  - AWS CodePipeline : Orchestrates the CI/SD Pipeline, Automating the build, test, and deployment stages
  - Amazon ECS : Deploys and manages containerized application using fargate for serverless container management
  - Amazon ECR : Stores and manages Docker images used in the ECS tasks
  - AWS CodeBuild : Handles the build phase of the pipeline, including Docker image creating
  - IAM Roles & Policies : Ensure secure access between the services involved
