---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Distributed platforms:
- Using Pulumi and Terraform as the IaC on AWS, I've setup:
-- SNS/SQS (encoded with protobuffers for avoid contract breaking and enabling versioning, all encoded/decoded on the edge)
-- Eventbridge (instead of SNS)
-- Eventbridge Scheduler (used to schedule events)
-- EKS (k8s)
-- Route53
-- Lambda's
-- Fargate
-- S3
-- DynamoDB
-- RDS
-- VPC
-- ALB
-- API Gateway
-- IAM, Security Groups, Policies
-- Prometheus/Grafana/OpenSearch (ie. ELK stack)
-- Alerting
-- Low hours down scaling

For product engineering managing the cloud resources, the DevEx done has been:
- Written an internal CLI tool used to both scaffold new services, and manage existing ones by:
-- Templating IaC code needed for new resources that you'd specify in a service manifest.
-- Handling dependencies and CI/CD automations
- Written an internal SDK library that would be used as abstractions in services used to:
-- Importing interfaces to interact with AWS resources, making the developer oblivious to the low level implementation and drive their focus towards building products.
-- Managing versions and creating a fault safe sandbox environment
-- Various testing methods
-- HTTP OpenAPI specs for auto generating API documentation for public/user facing products

Excerpt from CV:
* Designing and implementing core architecture, infrastructure solutions and tooling for a high scale, high throughput distributed event-driven platform on AWS.
* Responsible of providing libraries and interfaces with abstractions to pub/sub, database/storages and CLI tooling for product developers to build from and accelerate business logic.
* Providing infrastructure as code and internal tooling to automate creation and deployments of secure cloud microservices for multi environments in minutes on AWS using CI and laC.
