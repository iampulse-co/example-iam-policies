# Allow Cross-Account KMS Key Decryption to Specific IAM Roles
A policy that permits IAM roles from other accounts to decrypt KMS keys

- *Cloud Provider:* Amazon Web Services
- *Type:* Identity-Based
- *Referenced From:* https://docs.aws.amazon.com/kms/latest/developerguide/key-policies.html

## Instructions
Replace {{accountId}} with the id value of the account you wish to enable cross-account access from. 