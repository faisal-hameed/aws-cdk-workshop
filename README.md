# Welcome to your CDK TypeScript project!

Prerequisits : https://cdkworkshop.com/15-prerequisites/200-account.html

Tutorial : https://cdkworkshop.com/20-typescript.html  

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`CdkWorkshopStack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template


 ## CDK commands

 * `cdk init`      create new project with folder structure
 * `cdk diff`      check diffs between local files and deployed resources
 * `cdk deploy`    deploy current resources on cloud

 ### Testing AWS proxy integration

 `curl https://vpcvt5j0d7.execute-api.us-east-1.amazonaws.com/prod/`  
 It should return response like:  
 `Hello, CDK! You've hit /`

 ### Output with TableViewer construct 

<img src="./output-table.png" alt="Drawing" style="width: 800px;"/>


## Technologies used
- AWS CDK
- AWS Labmda
- AWS API Gateway
- AWS DynamoDB
- TableViewer construct
