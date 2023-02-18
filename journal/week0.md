# Week 0 — Billing and Architecture


We are developing Cruddur, a microblogging platform that will be similar to Twitter. The project is expected to take approximately 14 weeks to complete.

During the first week (actually the zero one), We integrated Gitpod with VSCode, set up the AWS CLI, and automated Gitpod workspaces to ensure the CLI is installed with every new workspace. 

We created flowcharts of the application using LucidChart, which was a great experience.

## Required Tasks:

- Completed all the required tasks.

### Cloud governace, IAM

Following best practice and using IAM user with admin and billing policies attached instead of root account. MFA enabled for user account.

![IAM-user](assets/week0-user.png)
![admin-billing](assets/week0-adminbilling.png)

### Conceptual Flow

High level Architecture design for all stakeholders.

![conceptual-diagram](assets/week0-conceptual-diagram.png)

### Logical Architecture Flow

Detailed design of the architecture for the technical team.

![main-diagram](assets/week0-logical-diagram-main.png)

### Budget And Billing Alarm creation

![budget](assets/budget-aws.png)
Created budget.

![billing-alert](assets/week0-billing-alert.png)
Created billing alert.

## Challenges:

Reviewed all the questions of each pillars in the Well Architected Tool

![well-architected-tool](assets/week0-well-architected.png)

### CI-CD Pipeline Design

Logical CI-CD pipeline for the application.

![pipeline-diagram](assets/week0-logical-diagram-pipeline.png)

## Obstacles:

I found to navigate through bash console it was my first time getting hands on this, also I got problems installing AWS on windows but finally I could manage it.

## Flowcharts
[My Diagrams from LucidChart](https://lucid.app/folder/invitations/accept/inv_f0c1c240-0da6-4a90-98de-e729db89f7d1)
