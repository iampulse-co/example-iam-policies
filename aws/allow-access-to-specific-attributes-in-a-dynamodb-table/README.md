# Allow Access to Specific Attributes in a DynamoDB Table
This policy grants permissions to perform actions on specific attributes in a DynamoDB table

- *Cloud Provider:* Amazon Web Services
- *Type:* Identity-Based
- *Referenced From:* https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_dynamodb_attributes.html

## Instructions
Replace {{tableName}} with the name of your DynamoDB table. Then for every attribute you wish to allow permissions for, specify the column name in the dynamodb:Attributes list. Once complete, attach the policy to an IAM Principal.