# AWS ECR Resource Policy: Block Outside Specific Public IP Range
Permits connection from only a specific public IP range

*Cloud Provider:* Amazon Web Services
*Type:* Identity-Based
*Referenced From:* https://docs.aws.amazon.com/AmazonECR/latest/userguide/repository-policy-examples.html

## Instructions
Replace {{ip-range}} with the CIDR block you wish to enable access from, blocking all access outside of.