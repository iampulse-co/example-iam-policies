# SCP: Require Amazon EC2 instances to use a specific type
This policy requires any EC2 instance spun up be of the specified type

- *Cloud Provider:* Amazon Web Services
- *Type:* Service Control Policy
- *Referenced From:* https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps_examples_ec2.html

## Instructions
Replace {{instance-type}} with the type of instance you wish to require (i.e. t2.micro)