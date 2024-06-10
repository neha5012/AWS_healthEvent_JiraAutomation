
# JIRA Automation with Serverless

## Introduction
This project sets up the infrastructure using serverless to automatically create JIRA tickets when a health issue appears on the AWS Health Dashboard.

## Prerequisites
Before you begin, ensure you have the following configured:

1. AWS Credentials
2. Python
3. npm
4. Serverless Framework

## Steps to Deploy

1. **Clone the Repository**

   Clone the repository containing the code.

2. **Deploy the Serverless Application**

   Run the following command to deploy the application using CloudFormation. This will deploy an AWS Lambda function with a Python runtime and create two EventBridge rules:

   ```sh
   serverless deploy
