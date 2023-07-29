# AWS-To-the-Power-Math
Design and build an end-to-end, fully functional math web application on AWS.

This project is all thansk to Tiny Technical Tutorials
https://www.youtube.com/watch?v=7m_q1ldzw0U&t=221s

## Five AWS services
* **Amplify:** Used to build and host websites, here we will be creating simple html page and then host it on Amplify.
* **Lambda:** Will use AWS Lambda to perform some basic math using Python.
* **API Gateway:** Have used REST API template. Copy the API Key for further use.
* **DynamoDB:** Create a basic database and store the ARN for further use. The ARN can be obtained from Overview -> General Information ->  Additional Info -> ARN
* **IAM (Identity and Access Manager):** We use this to provide the permission to write to our database.

<img src="/Services We'll be Using.png" />

## Deleting the resources
1. Delete the AWS Amplify domain that we created
2. DynamoDB --> Table --> Delete
3. Lamda Functions: Functions --> Select your function. --> Actions --> Delete
4. API Gateway: go to API's --> Select File --> Actions --> Delete
