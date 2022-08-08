# Allow AWS IAM Users Access to a Home S3 Bucket
Policy to enable users access to a specific directory in an S3 bucket based on username

- *Cloud Provider:* Amazon Web Services
- *Type:* Identity-Based
- *Referenced From:* https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_s3_home-directory-console.html

## Instructions
Replace {{bucketName}} with the name of the S3 bucket that contains home directories for each user. Note that the ${aws:username} is a dynamic AWS IAM policy variable.