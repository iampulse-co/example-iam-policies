# Deny AWS Access Based on Source IP
This policy denies access to all AWS actions in the account when the request comes from principals outside the specified IP range

*Cloud Provider:* Amazon Web Services
*Type:* Identity-Based
*Referenced From:* https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_aws_deny-ip.html

## Instructions
Replace {{sourceIP}} with the IP range you wish to enable access from, denying anything outside the range.