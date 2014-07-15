# Cloud Engineer Interview Audition

## Description

This is an opportunity to demonstrate your AWS cloud provider engineering ability
through code.

### Please be prepared to implement the following user story during your audition:

A 2 tiered application needs to be deployed out on AWS (Linux or Windows, your choice) which
will need to communicate back to your on premise data center. Please implement the following:

* deploy a highly available, 2 tiered application stack (back end DB services, front end web services) within
  a VPC
* configure an AutoScale group to dynamically scale your stack based on a http/https connection per host
  threshold via CloudWatch
* Create/Update the following tags:
  - Name
  - CostCenter
  - Owner

## Additional Information:

* we will provide you with access (both console and API) to an AWS account so don't worry about 
  creating/using your own
* feel free to use any research tools you have at your disposal (google, AWS docs, GitHub, etc, etc)

## Rules:

* please use any or all of the following methods/toolsets to implement this user story
  - AWS CLI tools (Windows or Linux based, your choice)
  - AWS SDK of your choice
  - CloudFormation templates
  - AWS Console
* Clone this repo to your GitHub account
* You can choose either Linux or Windows for your HA application stack
* Push up any scripts and/or code you plan on using to your cloned Github repo and be prepared to share 
  this information during the audition

**IF YOU CAN'T USE A PUBLIC REPO ON GITHUB, USE BITBUCKET [[ https://bitbucket.org/ ]] AND SET UP A PRIVATE REPO**