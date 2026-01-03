# Serverless Cloud Dictionary Application

### Project Overview:
In this project, we'll be developing a serverless cloud dictionary application where users can:

* Search for terms related to cloud technologies.
* View the definitions of cloud terms.
* Utilize a serverless architecture using AWS services.
* The application will use Lambda for backend processing, API Gateway for managing the API endpoints, and DynamoDB for storing the dictionary terms and their definitions.

The frontend, a React application, will be hosted on AWS Amplify, and API requests will be made to interact with the database.

### Services Used 🛠
* AWS Amplify: Host the frontend React application.
* AWS Lambda: Handle API requests for retrieving terms and adding new ones.
* AWS API Gateway: Manage API endpoints to allow communication between frontend and Lambda functions.
* AWS DynamoDB: Store dictionary terms and definitions.
* IAM Roles & Policies: Secure access to AWS resources like Lambda, DynamoDB, and API Gateway.

### Project Architecture:
<img width="1381" height="541" alt="image" src="https://github.com/user-attachments/assets/56a6c9b2-dece-49dc-ad62-29848fa59418" />

### Steps to be performed:
In the next few lessons, we'll be going through the following steps.

* Setup frontend and host it on AWS Amplify
* Configure DynamoDB to store Cloud Definitions
* Create Lambda function for fetching terms
* Setup API Gateway for API management
