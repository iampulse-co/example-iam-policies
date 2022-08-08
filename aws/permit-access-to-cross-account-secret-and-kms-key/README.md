# Permit Access to Cross-Account Secret and KMS Key
This policy allows principals to access cross-account secret and KMS CMK (decryption key)

*Cloud Provider:* Amazon Web Services
*Type:* Identity-Based
*Referenced From:* https://docs.aws.amazon.com/secretsmanager/latest/userguide/auth-and-access_examples.html

## Instructions
Replace {{region}} and {{account-id}} with the specific values for both Secrets Manager and KMS. Replace {{secret-name}} with the name of the secret you wish to enable access to, and {{kms-key-id}} with the decryption key id value.