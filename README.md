# mlinfratest
Test to implement secure ML infrastructure for model training and deployment to production 

Here is a sample user story with acceptance criteria that could be used to validate the infrastructure, ML and security skills of a lead DevOps engineer candidate:

Title: As a lead DevOps engineer, I need to set up a secure ML infrastructure for model training and deployment to production.

Description:
Set up a cloud-based infrastructure to handle an end-to-end machine learning pipeline from data ingestion to model deployment. Infrastructure should be scalable, secure, and auto-instrumented to gather metrics.

Acceptance Criteria:

Provision a VPC with public and private subnets across availability zones as per security best practices
Create compute resources spanning GPU and CPU instances for model training and hosting services
Build containerization infrastructure for ML training jobs and hosting ML model APIs
Establish data storage layer spanning raw, transformed, and model artifact data
Implement identity and access management for least-privilege security
Set up CI/CD pipeline for continuous model retraining and canary deployments
Instrument infrastructure end-to-end for observability into utilization metrics
Create dashboards for monitoring ML pipeline health, security, costs and performance
Handle a simulated rolling upgrade of ML infrastructure without model downtime
Run a chaos test by randomly terminating resources to validate resilience
