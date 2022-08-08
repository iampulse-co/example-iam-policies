# Allow Principals to Encrypt via KMS but Deny Decrypt via KMS
Secrets decryption is a sensitive operation and should not be done by most humans principals (e.g. federated roles).

- *Cloud Provider:* Amazon Web Services
- *Type:* Identity-Based