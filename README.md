# number-power-project

Calculate the power of a number using AWS Serverless Architecture.
Built by following an AWS tutorial as part of my cloud learning journey.

## Architecture
<img width="2720" height="1280" alt="aws_serverless_architecture" src="https://github.com/user-attachments/assets/c7ac006a-3fff-4c9c-bfef-d805159a22bb" />


## AWS Services Used:
- AWS Amplify — Frontend hosting
- AWS Lambda — Serverless compute function
- API Gateway — REST API to invoke Lambda
- DynamoDB — NoSQL database to store results
- IAM — Permissions management for Lambda to access DynamoDB

## How it works:
1. User enters a base number and exponent on the webpage
2. Clicking Calculate sends a request via API Gateway
3. Lambda function runs the calculation
4. Result is stored in DynamoDB and returned to the user

## Output:
<img width="1562" height="923" alt="number power proj output" src="https://github.com/user-attachments/assets/e5a9266f-c1e7-4f16-8485-82e421207511" />


## Notes:
AWS resources have been cleaned up post-demo to manage cloud costs.
