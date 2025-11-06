# StackCentralizer

**StackCentralizer** is a central knowledge hub that organizes all my tech stacks, tools, and real-world projects into a structured and searchable format.

---

## Index

- [API Development](#api-development)
- [Messaging and Event-Driven Architecture](#messaging-and-event-driven-architecture)
- [Cloud and DevOps](#cloud-and-devops)
  - [AWS](#aws)
  - [Azure](#azure)
- [Data and Storage](#data-and-storage)
  - [Relational Databases](#relational-databases)
  - [NoSQL and Caching](#nosql-and-caching)
  - [ORM and Data Access](#orm-and-data-access)
- [Architecture and Design Patterns](#architecture-and-design-patterns)
- [Job Scheduling and Background Tasks](#job-scheduling-and-background-tasks)
- [Authentication and Authorization](#authentication-and-authorization)
- [Testing and Code Quality](#testing-and-code-quality)
- [Utilities and Developer Tools](#utilities-and-developer-tools)
- [Templates and Boilerplates](#templates-and-boilerplates)
- [Global Tags](#global-tags)


---


## API Development

- [EShopMicroservices](https://github.com/antonioscript/EShopMicroservices)  
  Full-featured .NET microservices e-commerce application demonstrating best practices for distributed systems. Includes APIs, RabbitMQ, Redis cache, PostgreSQL, MongoDB, CQRS with MediatR, Entity Framework, and the Marten library.  
  Tags: `dotnet`, `api`, `microservices`, `rabbitmq`, `redis`, `postgresql`, `mongodb`, `marten`, `cqrs`, `mediatr`, `entity-framework`, `orm`, `architecture`, `cache`, `sql`, `nosql`, `containers`, `docker`, 'jwt', 'token', `authentication`, `architecture`

- [MedicalClinicAPI](https://github.com/antonioscript/MedicalClinicAPI)  
  Modular .NET application simulating a medical clinic system. Includes RESTful APIs, MediatR, Clean Architecture, PostgreSQL, Redis cache, CQRS, and Entity Framework.  
  Tags: `dotnet`, `api`, `clean-architecture`, `mediatr`, `cqrs`, `postgresql`, `redis`, `entity-framework`, `architecture`, `cache`, `sql`, jwt', 'token', `authentication`, `architecture`

- [Microservices.AKS.Devops](https://github.com/antonioscript/Microservices.AKS.Devops)  
  Microservices project with .NET APIs deployed on Azure Kubernetes Service (AKS) with CI/CD pipelines. Includes Docker, Kubernetes, Redis, PostgreSQL, RabbitMQ, and DevOps infrastructure as code.  
  Tags: `dotnet`, `api`, `microservices`, `aks`, `kubernetes`, `devops`, `azure`, `ci-cd`, `rabbitmq`, `redis`, `postgresql`, `cloud`, `infrastructure`, `sql`, `messaging`, `containers`, `docker`, `architecture`

- [RedisAPI.NET](https://github.com/antonioscript/RedisAPI.NET)  
  .NET API example that demonstrates integration with Redis for caching and fast data retrieval. Useful for scenarios requiring low-latency key-value access.  
  Tags: `redis`, `nosql`, `caching`, `dotnet`, `api`, `performance`

- [AutomativeRepairAPI](https://github.com/antonioscript/AutomativeRepairAPI)  
  RESTful API for an automotive repair system built with NestJS and TypeScript. Implements real-world modules, domain logic, and separation of concerns.  
  Tags: `nestjs`, `typescript`, `nodejs`, `api`, `rest`, `domain`, `automotive`

- [HeroAPI](https://github.com/antonioscript/HeroAPI)  
  Hero management API built using NestJS and TypeScript. Includes routing, services, and domain-layer organization for real-world backend patterns.  
  Tags: `nestjs`, `typescript`, `nodejs`, `api`, `rest`, `heroes`, `domain`

- [TodoAPI.MinimalAPI](https://github.com/antonioscript/TodoAPI.MinimalAPI)  
  .NET Minimal API example for simple CRUD operations using a lightweight HTTP interface. Demonstrates practical usage of modern .NET endpoints.  
  Tags: `dotnet`, `api`, `minimal-api`, `rest`, `crud`, `lightweight`

- [RelationshipsAPI](https://github.com/antonioscript/RelationshipsAPI/tree/master)  
  Demonstrates relationship handling in .NET Minimal API. Covers one-to-one, one-to-many, and many-to-many entity mappings using EF Core.  
  Tags: `dotnet`, `api`, `minimal-api`, `relationships`, `entity-framework`, `ef-core`, `database`


---

## Messaging and Event-Driven Architecture

- [RabbitMQProducerConsumer](https://github.com/antonioscript/RabbitMQProducerConsumer)  
  Basic example of a producer and consumer using RabbitMQ with native client libraries. Good for learning core messaging concepts like queues and exchanges.  
  Tags: `rabbitmq`, `messaging`, `producer`, `consumer`, `dotnet`, `queue`

- [RabbitMQ.MassTransit](https://github.com/antonioscript/RabbitMQ.MassTransit)  
  Implementation using MassTransit to simplify RabbitMQ integration in .NET applications. Demonstrates publishers, consumers, and message configuration.  
  Tags: `rabbitmq`, `masstransit`, `messaging`, `event-driven`, `dotnet`

- [MicroRabbit](https://github.com/antonioscript/MicroRabbit)  
  Microservice-based architecture using RabbitMQ for event-driven communication in a modular .NET solution. Good reference for domain-driven message flows.  
  Tags: `rabbitmq`, `messaging`, `microservices`, `event-driven`, `dotnet`

- [AWS.SQS.NET](https://github.com/antonioscript/AWS.SQS.NET)  
  See main entry in: [AWS](#aws)

---

## Cloud and DevOps

### AWS

- [AWS.NET](https://github.com/antonioscript/AWS.NET)  
  Repository created to organize .NET applications using AWS services. Acts as a central index for Lambda, EC2, S3, VPC, and more.  
  Tags: `aws`, `dotnet`, `cloud`, `architecture`, `centralizer`, `infrastructure`

- [AWS.Lambda.NET](https://github.com/antonioscript/AWS.Lambda.NET)  
  Serverless function examples using AWS Lambda with .NET. Demonstrates setup, triggers, handlers, and deployment via AWS CLI or SAM.  
  Tags: `aws`, `lambda`, `serverless`, `dotnet`, `cloud`, `functions`

- [API.NET.AWS.Lambda](https://github.com/antonioscript/API.NET.AWS.Lambda)  
  Example of a .NET API deployed to AWS Lambda using API Gateway. Combines RESTful endpoints with serverless execution.  
  Tags: `aws`, `lambda`, `api`, `serverless`, `dotnet`, `api-gateway`

- [API.NET.AWS.EC2](https://github.com/antonioscript/API.NET.AWS.EC2)  
  Hosting a .NET Web API on an EC2 instance. Includes deployment scripts, configuration, and setup for virtual servers.  
  Tags: `aws`, `ec2`, `dotnet`, `api`, `infrastructure`, `compute`, `virtual-machine`

- [API.NET.SimpleCluster.ECS](https://github.com/antonioscript/API.NET.SimpleCluster.ECS)  
  Simple ECS cluster setup using Fargate to deploy a .NET API in containers. Includes service/task definitions and load balancing.  
  Tags: `aws`, `ecs`, `fargate`, `api`, `cluster`, `containers`, `dotnet`

- [API.NET.AWS.ECS](https://github.com/antonioscript/API.NET.AWS.ECS)  
  Docker-based .NET API deployed to AWS ECS with scalable infrastructure. Focuses on container orchestration and networking.  
  Tags: `aws`, `ecs`, `docker`, `containers`, `api`, `dotnet`, `devops`

- [AWS.VPC](https://github.com/antonioscript/AWS.VPC)  
  Configuration and management of custom Virtual Private Clouds (VPC) in AWS. Includes subnets, route tables, and security groups.  
  Tags: `aws`, `vpc`, `networking`, `cloud`, `infrastructure`, `devops`

- [AWS.IAM](https://github.com/antonioscript/AWS.IAM)  
  Identity and Access Management (IAM) examples for defining users, roles, and policies in AWS.  
  Tags: `aws`, `iam`, `security`, `roles`, `policies`, `access-control`

- [API.NET.AWS.S3](https://github.com/antonioscript/API.NET.AWS.S3)  
  File upload/download integration with AWS S3 from a .NET API. Demonstrates bucket access, presigned URLs, and storage operations.  
  Tags: `aws`, `s3`, `dotnet`, `storage`, `files`, `api`, `cloud`

- [AWS.CloudWatch](https://github.com/antonioscript/AWS.CloudWatch)  
  Monitoring and logging in AWS with CloudWatch. Covers custom metrics, logs, dashboards, and alarms.  
  Tags: `aws`, `cloudwatch`, `monitoring`, `logging`, `observability`, `metrics`

- [AWS.APIGateway.NET](https://github.com/antonioscript/AWS.APIGateway.NET)  
  Gateway configurations to expose and secure .NET APIs via AWS API Gateway. Supports custom domains, stages, and throttling.  
  Tags: `aws`, `api-gateway`, `api`, `dotnet`, `gateway`, `rest`, `lambda`, `dynamo-db`

- [AWS.Cognito.NET](https://github.com/antonioscript/AWS.Cognito.NET)  
  Authentication via AWS Cognito in .NET apps. Includes user pool setup, token validation, and secured routes.  
  Tags: `aws`, `cognito`, `auth`, `jwt`, `security`, `dotnet`

- [AWS.Route53](https://github.com/antonioscript/AWS.Route53)  
  DNS management using AWS Route 53. Demonstrates hosted zones, record sets, and domain routing.  
  Tags: `aws`, `route53`, `dns`, `networking`, `cloud`, `infrastructure`

- [AWS.ElasticLoadBalancing](https://github.com/antonioscript/AWS.ElasticLoadBalancing)  
  Setup of Application and Network Load Balancers (ALB/NLB) for .NET services. Includes listener rules and target groups.  
  Tags: `aws`, `elb`, `alb`, `nlb`, `load-balancer`, `cloud`, `dotnet`

- [AWS.SQS.NET](https://github.com/antonioscript/AWS.SQS.NET)  
  Integration with AWS Simple Queue Service (SQS) using .NET. Demonstrates sending and receiving messages through AWS-managed queues.  
  Tags: `aws`, `sqs`, `cloud`, `messaging`, `dotnet`, `queue`

- [AWS.SNS.NET](https://github.com/antonioscript/AWS.SNS.NET)  
  Pub/Sub messaging in AWS using Simple Notification Service (SNS). Includes topic creation, subscriptions, and publishing from .NET.  
  Tags: `aws`, `sns`, `messaging`, `pubsub`, `dotnet`, `notifications`


### Azure

- [Azure.NET](https://github.com/antonioscript/Azure.NET)  
  Centralized index of Azure-related projects using .NET technologies. Serves as a launch point for exploring services such as Blob Storage, AKS, CI/CD, and other cloud-native patterns in Azure.  
  Tags: `azure`, `cloud`, `dotnet`, `centralizer`, `index`, `devops`, `infrastructure`

- [Azure.AWS](https://github.com/antonioscript/Azure.AWS)  
  Azure.AWS is a comparative guide that highlights the key differences and similarities between Microsoft Azure and Amazon Web Services (AWS)  
  Tags: `azure`, `cloud`,`devops`, `infrastructure`, `aws`

- [AzureBlobStorage](https://github.com/antonioscript/AzureBlobStorage)  
  .NET implementation for interacting with Azure Blob Storage. Demonstrates file upload, download, container configuration, and secure access.  
  Tags: `azure`, `blob-storage`, `cloud`, `storage`, `dotnet`, `files`, `containers`


---

## Data and Storage

### Relational Databases

- [CommandsSQL](https://github.com/antonioscript/CommandsSQL)  
  Collection of raw SQL scripts and command examples for working with relational databases. Includes queries, table creation, joins, and more.  
  Tags: `sql`, `relational-db`, `queries`, `database`, `postgresql`

### NoSQL and Caching

- [MongoDB](https://github.com/antonioscript/MongoDB)  
  Introductory MongoDB project demonstrating connection and basic operations using JavaScript or Node.js.  
  Tags: `mongodb`, `nosql`, `database`

- [MongoDB.NET](https://github.com/antonioscript/MongoDB.NET)  
  Integration of MongoDB in a .NET application using the official driver. Includes models, repositories, and connection setup.  
  Tags: `mongodb`, `nosql`, `dotnet`, `database`

- [MongoDB.NET](https://github.com/antonioscript/MongoDB.NET)  
  Integration of MongoDB in a .NET application using the official driver. Includes models, repositories, and connection setup.  
  Tags: `mongodb`, `nosql`, `dotnet`, `database`

- [DinamicAPI.NoSQL.NET](https://github.com/antonioscript/DinamicAPI.NoSQL.NET)  
  API created to simulate request and sending of dynamic objects and storing in the NoSQL Data MongoDB and DynamoDB
  Tags: `mongodb`, `nosql`, `dotnet`, `database`, `dinamodb`,`dinamic`

### ORM and Data Access

- [EntityFramework](https://github.com/antonioscript/EntityFramework)  
  Practical examples of using Entity Framework in .NET applications. Demonstrates database modeling, DbContext, migrations, and LINQ queries.  
  Tags: `dotnet`, `entity-framework`, `orm`, `database`, `migrations`, `linq`, `data-access`

---

## Architecture and Design Patterns

- [Middleware.NET](https://github.com/antonioscript/Middleware.NET)  
  Demonstrates the use of middleware as a form of Chain of Responsibility and separation of concerns.  
  Tags: `dotnet`, `middleware`, `design-patterns`, chain-of-responsibility`
  

- [MediatorNET](https://github.com/antonioscript/MediatorNET)  
  Demonstrates the Mediator design pattern in .NET using MediatR for internal messaging, command/query separation, and loose coupling between components.  
  Tags: `dotnet`, `mediator`, `design-patterns`, `cqrs`, `mediatR`, `architecture`

- [UnitOfWork](https://github.com/antonioscript/UnitOfWork/tree/master)  
  Implementation of the Unit of Work and Repository patterns in .NET. Useful for managing transactions and consistency across multiple repositories.  
  Tags: `dotnet`, `unit-of-work`, `repository-pattern`, `architecture`, `design-patterns`, `transaction`


---

## Job Scheduling and Background Tasks

- [API.Hangfire.NET](https://github.com/antonioscript/API.Hangfire.NET)  
  Background job processing in .NET using Hangfire. Includes scheduled tasks, retries, dashboard UI, and integration with ASP.NET APIs.  
  Tags: `dotnet`, `hangfire`, `jobs`, `background-tasks`, `scheduler`, `queue`, `aspnetcore`


---

## Authentication and Authorization

- [ApiWebIdentity](https://github.com/antonioscript/ApiWebIdentity)  
  ASP.NET Core API demonstrating authentication and authorization using ASP.NET Identity. Includes user registration, JWT, claims, and role-based access control.  
  Tags: `dotnet`, `aspnetcore`, `authentication`, `authorization`, `identity`, `jwt`, `security`

---

## Testing and Code Quality

- [Dotnet.Tests](https://github.com/antonioscript/Dotnet.Tests)  
  Unit testing examples in .NET using xUnit and related tools. Demonstrates test organization, assertions, dependency mocking, and general testing strategies.  
  Tags: `dotnet`, `testing`, `unit-tests`, `xunit`, `moq`, `code-quality`, `tdd`

---

## Utilities and Developer Tools

- [VisualStudioCode.Tips](https://github.com/antonioscript/VisualStudioCode.Tips)  
  A collection of tips, extensions, shortcuts, and settings for improving productivity with Visual Studio Code.  
  Tags: `vscode`, `tips`, `editor`, `developer-tools`, `productivity`

- [Cheatsheets_and_Codes](https://github.com/antonioscript/Cheatsheets_and_Codes)  
  A collection of cheatsheets and code snippets for quick reference across multiple technologies. Ideal for study reinforcement and fast lookup.  
  Tags: `cheatsheet`, `snippets`, `reference`, `learning`, `developer-tools`, `study`

---

## Templates and Boilerplates

- [Curso-Csharp-Dotnet](https://github.com/antonioscript/Curso-Csharp-Dotnet)  
  A complete C# and .NET learning repository covering syntax, object-oriented programming, data structures, and platform basics. Useful as a study base or quick reference.  
  Tags: `dotnet`, `csharp`, `learning`, `fundamentals`, `oop`, `curso`

- [TypeScriptBasic](https://github.com/antonioscript/TypeScriptBasic)  
  Basic TypeScript learning repository covering the core features of the language such as types, functions, interfaces, generics, and more.  
  Tags: `typescript`, `learning`, `language`, `fundamentals`, `boilerplate`

- [NestJSJourney](https://github.com/antonioscript/NestJSJourney)  
  A step-by-step study path for understanding NestJS core concepts. Includes isolated examples of modules, controllers, services, decorators, and more.  
  Tags: `nestjs`, `typescript`, `nodejs`, `learning`, `study`, `backend-framework`

- [CustomLibrary.NET](https://github.com/antonioscript/CustomLibrary.NET)  
  A reusable .NET library designed to simplify and standardize common operations across multiple applications.  
  Tags: `dotnet`, `library`,  `nuget`,  `package`


- [DefaultSystem](https://github.com/antonioscript/DefaultSystem)  
  Standard .NET source code template for building APIs following the Onion Architecture pattern. Includes layered organization, abstractions, and clean separation of concerns.  
  Tags: `dotnet`, `onion-architecture`, `api`, `template`, `clean-code`, `boilerplate`

- [MapperApp](https://github.com/antonioscript/MapperApp)  
  Template project showcasing practical use of mapping between domain and view models using libraries like AutoMapper in .NET.  
  Tags: `dotnet`, `automapper`, `mapper`, `template`, `boilerplate`, `architecture`

- [Dotnet-Essential](https://github.com/antonioscript/Dotnet-Essential/tree/master)  
  Essential .NET boilerplate with core setup, base layers, and reusable components for kickstarting new projects.  
  Tags: `dotnet`, `starter`, `boilerplate`, `template`, `essentials`, `setup`


---

## Global Tags

`ak` · `alb` · `api` · `api-gateway` · `architecture` · `aspnetcore` · `authentication` · `authorization` · `aws` · `azure` · `background-tasks` · `boilerplate` · `cache` · `caching` · `centralizer` · `cheatsheet` · `ci-cd` · `clean-architecture` · `cloud` · `cluster` · `code-quality` · `compute` · `containers` · `course` · `crud` · `csharp` · `database` · `data-access` · `design-patterns` · `developer-tools` · `devops` · `dns` · `docker` · `domain` · `dotnet` · `ecs` · `editor` · `ef-core` · `elb` · `entity-framework` · `essentials` · `event-driven` · `fargate` · `files` · `functions` · `fundamentals` · `gateway` · `hangfire` · `heroes` · `identity` · `index` · `infrastructure` · `javascript` · `jobs` · `jq` · `jwt` · `kubernetes` · `language` · `learning` · `linq` · `load-balancer` · `logging` · `mapper` · `masstransit` · `mediator` · `mediatR` · `messaging` · `metrics` · `microservices` · `minimal-api` · `migrations` · `moq` · `monitoring` · `mongodb` · `marten` · `networking` · `nestjs` · `nodejs` · `nosql` · `notifications` · `oauth` · `onion-architecture` · `oop` · `orm` · `performance` · `pg` · `postgresql` · `policies` · `productivity` · `pubsub` · `queue` · `queries` · `rabbitmq` · `reference` · `relational-db` · `repository-pattern` · `rest` · `roles` · `route53` · `scheduler` · `security` · `serverless` · `setup` · `snippets` · `sql` · `starter` · `storage` · `study` · `template`, `dinamic`, `dinamodb`,  `library`,  `nuget`,  `package`


---

This repository is a living document and will be updated regularly as I continue to grow and build.
