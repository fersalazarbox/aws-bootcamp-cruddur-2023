# Week 0 — Billing and Architecture

We are developing Cruddur, a microblogging platform that will be similar to Twitter. The project is expected to take approximately 14 weeks to complete.

During the week 'zero' in the bootcamp, I accomplished several tasks related to preparing for cloud engineering on AWS. I gained a thorough understanding of billing and architecture in AWS, which involved learning about the pricing differences between regions, and how to monitor and manage costs. For instance, I created Budgets to track expenses across resources and set up free-tier monitoring.

I also learned about security practices in AWS and how to protect data within cloud-hosted applications. I discovered the importance of an AWS account compromise and explored some basic practices to mitigate the risks. These services include AWS Organizations, which allows for account segregation and helps with managing security and billing, and AWS CloudTrail, a monitoring tool that can log and track most activities within my AWS account.

I completed several assignments during the week, including creating an admin user, installing the AWS CLI, and creating a billing alarm and budget. I also worked on some required homework such as recreating a conceptual and logical architectural diagram using LucidChart, enabling MFA for both my root and IAM users, and setting up AWS CLI environment variables.

For me, the most important lesson was understanding how to understand the proposal of high-level solutions and approaches for projects to decision-makers. I realized that it is crucial to understand business objectives and to present viable solutions that will achieve the desired outcomes.

Overall, the foundational tasks related to billing, security, and architecture that I learned during the zero week will be instrumental in my journey towards becoming a proficient cloud engineer on AWS. I am excited to continue building on these foundations in the coming weeks.


## Required Tasks:

- Completed all the required tasks.

### Cloud governace, IAM

Following best practice and using IAM user with admin and billing policies attached instead of root account. MFA enabled for user account.

![IAM-user](assets/week0-user.png)
![admin-billing](assets/week0-adminbilling.png)

### Conceptual Flow

High level Architecture design for all stakeholders.

![conceptual](../_docs/assets/CRUDDUR-Napkin-flow.png)

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
