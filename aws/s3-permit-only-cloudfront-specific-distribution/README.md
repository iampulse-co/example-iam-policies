# S3: Permit Only CloudFront Specific Distribution
For public access, permit only a specific CloudFront distribution

*Cloud Provider:* Amazon Web Services
*Type:* Resource-Based
*Referenced From:* https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-restricting-access-to-s3.html

## Instructions
Replace {{cloudfront-oai-id}} with the CloudFront Origin Access identity. Replace {{bucket-name}} with the name of the S3 bucket.