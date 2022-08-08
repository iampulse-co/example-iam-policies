# Limit S3 Web Access to Specific Public IPs
This bucket policy restricts access to S3 from select ip ranges

- *Cloud Provider:* Amazon Web Services
- *Type:* Resource-Based
- *Referenced From:* https://docs.aws.amazon.com/AmazonS3/latest/userguide/example-bucket-policies.html#example-bucket-policies-use-case-3

## Instructions
Replace {{bucket-name}} with the name of the S3 bucket you wish to protect. Then replace {{user-ip}} with the IP range you wish to allow access from.