# AWS-web-application-using-AWS-S3-Lambda-DynamoDB-API-Cloudfront

This is a serverless web application using various AWS services. Steps taken from setting up an S3 bucket to host the static website, configuring API Gateway to trigger Lambda functions for handling GET and POST requests to interact with a DynamoDB database and securing the application with Cloudfront.

S3 bucket to host static web content, including HTML, CSS AND JavaScript files.

Configure API Gateway(REST) to trigger Lambda functions. Set up GET and POST methods to interact with DynamoDB database.

Create Lambda functions in Python to handle the API Gateway requests. Functions to retrieve data from DynamoDB and insert new data into it. IAM role created to allow access to DynamoDB

Set up a DynamoDB table to store our data.

Secure the application using cloudfront. This provides encryption in transit and improves the performance of the application.

Codes used for this projects is included in the respository.
