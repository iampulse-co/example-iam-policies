# Attach or Detach Volumes to an EC2 Instance based on Tags
This policy allows EBS owners to attach or detach volumes to instances that match a specific tag

*Cloud Provider:* Amazon Web Services
*Type:* Identity-Based
*Referenced From:* https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_ec2_ebs-owner.html

## Instructions
Replace {{tagName}} and {{tagValue}} with the tag pair you wish to set as a condition. Also replace {{EBSOwnerTag}} with the name of the tag that includes the owner username as the value.