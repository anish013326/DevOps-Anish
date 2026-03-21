# DevOps-Anish
## DevOps Interview Questions & Answers

Click ⭐ if you like the project. Pull Requests are highly appreciated.

> This repository contains DevOps interview questions and answers. Please check the different sections for specific topics like Docker, Kubernetes, CI/CD, etc.

## Table of Contents

| No. | Questions |
|-----|-----------|
| 1 | [What is DevOps?](#what-is-devops) |
| 2 | [What are the benefits of DevOps?](#what-are-the-benefits-of-devops) |
| 3 | [What is Continuous Integration?](#what-is-continuous-integration) |
| 4 | [What is Continuous Delivery?](#what-is-continuous-delivery) |
| 5 | [What is Continuous Deployment?](#what-is-continuous-deployment) |

### Core DevOps Concepts

#### What is DevOps?
*DevOps is a set of practices that combines software development (Dev) and IT operations (Ops). It aims to shorten the systems development life cycle and provide continuous delivery with high software quality. DevOps is complementary with Agile software development; several DevOps aspects came from Agile methodology.*

#### What are the benefits of DevOps?
*The main benefits of DevOps include:

Faster delivery of features
More stable operating environments
Improved communication and collaboration
More time to innovate (rather than fix/maintain)
Reduced deployment failures and rollbacks
Shorter mean time to recovery*

#### What is Continuous Integration?
*Continuous Integration (CI) is a development practice where developers integrate code into a shared repository frequently, preferably several times a day. Each integration can then be verified by an automated build and automated tests.

Key aspects of CI include:

Maintaining a single source repository
Automating the build
Making the build self-testing
Everyone commits to the baseline every day
Every commit builds on an integration machine
Keep the build fast
Test in a clone of the production environment
Make it easy to get the latest deliverables
Everyone can see the results of the latest build
Automate deployment*

#### What is Continuous Delivery?
*Continuous Delivery is a DevOps practice where code changes are automatically built, tested, and prepared for production release. The core goal is to ensure the software is always in a releasable state. 

The key differentiator is that while the entire pipeline is automated up to the staging environment, the final deployment to production requires a manual approval or trigger based on business readiness.*

#### What is Continuous Deployment?
*Continuous Deployment is a DevOps practice where every code change that passes all stages of your automated production pipeline is released to your customers automatically. 

The key differentiator between this and Continuous Delivery is that there is absolutely no human intervention. Only a failed automated test will prevent a new change from being deployed to production. Because of this, it requires a highly mature and robust automated testing suite.
*