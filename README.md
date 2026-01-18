Serverless Event-driven E-commerce Microservices
<img width="1794" height="781" alt="image" src="https://github.com/user-attachments/assets/bd230655-a139-4c2e-9a9e-a1bea8dd5d80" />
This is a Serverless Event-driven E-commerce project for TypeScript development with CDK. The cdk.json file tells the CDK Toolkit how to execute your app.

Check Explanation of this Repository on Medium
AWS Event-driven Serverless Microservices using AWS Lambda, API Gateway, EventBridge, SQS, DynamoDB and CDK for IaC
See All Articles - AWS Serverless Microservices with Patterns & Best Practices
Whats Including In This Repository
We will be following the reference architecture above which is a real-world Serverless E-commerce application and it includes;

REST API and CRUD endpoints with using AWS Lambda, API Gateway
Data persistence with using AWS DynamoDB
Decouple microservices with events using Amazon EventBridge
Message Queues for cross-service communication using AWS SQS
Cloud stack development with IaC using AWS CloudFormation and AWS CDK
Prerequisites
You will need the following tools:

AWS Account and User
AWS CLI
NodeJS
AWS CDK Toolkit
Docker
Run The Project
Follow these steps to get your development environment set up: (Before Run Start the Docker Desktop)

Clone the repository
At the root directory which include cdk.json files, run below command:
cdk deploy
Note: Make sure that your Docker Desktop is running before execute the cdk deploy command.

Wait for provision all microservices into aws cloud. That’s it!

You can launch microservices as below urls:

Product API -> https://xxx.execute-api.ap-southeast-1.amazonaws.com/prod/product
Basket API -> https://xxx.execute-api.ap-southeast-1.amazonaws.com/prod/basket
Ordering API -> https://xxx.execute-api.ap-southeast-1.amazonaws.com/prod/order
Useful commands
npm run build compile typescript to js
npm run watch watch for changes and compile
npm run test perform the jest unit tests
cdk deploy deploy this stack to your default AWS account/region
cdk diff compare deployed stack with current state
cdk synth emits the synthesized CloudFormation template
