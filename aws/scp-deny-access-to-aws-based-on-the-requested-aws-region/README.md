# SCP: Deny access to AWS based on the requested AWS Region
This SCP denies access to any operations outside of the specified Regions.

- *Cloud Provider:* Amazon Web Services
- *Type:* Service Control Policy
- *Referenced From:* https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps_examples_general.html#example-scp-deny-region

## Instructions
Replace the {{regionN}} variables with any regions you wish to restrict access to.