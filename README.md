# Terraform AWS Serverless Test Project

This is a serverless project based on AWS Serverless stack which are configured through terraform. This application includes a basic lambda secured by Cognito and triggered through AWS API Gateway. This function will upload file to AWS S3 and storing its information to AWS DynamoDB.

## Technical resources used for this project are

1. Terraform (Typescript - [CDKIT](https://www.npmjs.com/package/cdktf-cli))
2. Node.JS
3. AWS Cognito (username) for authentication
4. DynamoDB
5. AWS Lambda (Functions)
6. AWS API Gateway (Endpoints/API Keys/Lambda Authorizers w/Cognito)

## Usage

```bash
npm install
```
