# Allow a Lambda Function to Access a DynamoDB Table
An IAM policy to attach to a Lambda function role to allow access to a specific DynamoDB table

- *Cloud Provider:* Amazon Web Services
- *Type:* Identity-Based
- *Referenced From:* https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_lambda-access-dynamodb.html

## Instructions
Replace {{dynamoTable}} with the name of the DynamoDB table you wish to allow Lambda access to. Attach this policy to the execution role for the Lambda function.