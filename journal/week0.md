# Week 0 — Billing and Architecture

We are developing Cruddur, a microblogging platform that will be similar to Twitter. The project is expected to take approximately 14 weeks to complete.

During the week 'zero' in the bootcamp, I accomplished several tasks related to preparing for cloud engineering on AWS. I gained a thorough understanding of billing and architecture in AWS, which involved learning about the pricing differences between regions, and how to monitor and manage costs. For instance, I created Budgets to track expenses across resources and set up free-tier monitoring.

I also learned about security practices in AWS and how to protect data within cloud-hosted applications. I discovered the importance of an AWS account compromise and explored some basic practices to mitigate the risks. These services include AWS Organizations, which allows for account segregation and helps with managing security and billing, and AWS CloudTrail, a monitoring tool that can log and track most activities within my AWS account.

I completed several assignments during the week, including creating an admin user, installing the AWS CLI, and creating a billing alarm and budget. I also worked on some required homework such as recreating a conceptual and logical architectural diagram using LucidChart, enabling MFA for both my root and IAM users, and setting up AWS CLI environment variables.

For me, the most important lesson was understanding how to understand the proposal of high-level solutions and approaches for projects to decision-makers. I realized that it is crucial to understand business objectives and to present viable solutions that will achieve the desired outcomes.

Overall, the foundational tasks related to billing, security, and architecture that I learned during the zero week will be instrumental in my journey towards becoming a proficient cloud engineer on AWS. I am excited to continue building on these foundations in the coming weeks.


## Required Tasks:
- [X] Re-create Cruddur's Conceptual Diagram 
- [X] Re-create Cruddur's Logical Diagram 
- [X] Install and verify the AWS CLI on Gitpod
- [X] Create Billing and Budget Alarms 


## Install and verify AWS CLI 
To install the AWS CLI on our gitpod workspace we added a gitpod **task** using by adding the following configuration into our `.gitpod.yml` file: 

```yml
tasks:
  - name: aws-cli
    env:
      AWS_CLI_AUTO_PROMPT: on-partial
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
...
```

To connect our AWS account we had to provide Environment variables into GitPod

### Cloud governace, IAM

MFA enabled for root and user account. Following best practices and using IAM user with admin and billing policies attached instead of root account. 



### Conceptual Flow

High level Architecture design for all stakeholders.

![conceptual](../_docs/assets/CRUDDUR-Napkin-flow.png)

### Logical Architecture Flow

Detailed design of the architecture for the technical team.


### Budget And Billing Alarm creation


## Challenges:

Reviewed all the questions of each pillars in the Well Architected Tool



### CI-CD Pipeline Design

Logical CI-CD pipeline for the application.


## Obstacles:


## Flowcharts from Luchidchart
[My Diagrams from LucidChart](https://lucid.app/folder/invitations/accept/inv_f0c1c240-0da6-4a90-98de-e729db89f7d1)
