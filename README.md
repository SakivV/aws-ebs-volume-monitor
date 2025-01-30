# AWS-EBS-Volume-Monitor
This solution checks if EBS volumes are in Available state means not attached to any EC2 instnace. Once identify, it will delete EBS volume by taking snapshot.

## Parameters
| Name | Type | Description |
|:-----------|:-----------:|------------:|
| RuleName     | String      | User define rule name      |
| IsSnpashotRequired    | Boolean     | True if you need snapshot needs to be take before delete     |


![aws_ebs_usage](./aws_ebs_monitor_nt.png)


