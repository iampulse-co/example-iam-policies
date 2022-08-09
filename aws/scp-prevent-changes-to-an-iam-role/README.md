# SCP: Prevent changes to an IAM Role
This SCP prevents principals from making IAM changes to a specified IAM Role

- *Cloud Provider:* Amazon Web Services
- *Type:* Service Control Policy
- *Referenced From:* https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps_examples_general.html#example-scp-restricts-iam-principals

## Instructions
Replace {{role-name}} with the name of the IAM Role you wish to prevent any changes to.