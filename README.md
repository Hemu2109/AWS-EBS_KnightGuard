# AWS-EBS_KnightGuard

## Objective
Automated the compliance monitoring and remediation of unencrypted EBS volumes to ensure adherence to security policies.

## Tools & Technologies
AWS Config, AWS Lambda, Amazon EventBridge (CloudWatch Events), AWS CloudWatch, Python.

## Key Responsibilities
- Configured AWS Config rules to monitor EBS volume encryption status.
- Developed a Lambda function in Python to automatically encrypt non-compliant EBS volumes.
- Set up EventBridge rules to trigger the Lambda function upon detection of non-compliant resources.
- Validated compliance status through AWS Config and AWS Security Hub, ensuring real-time compliance reporting.

## Outcome
Enhanced security posture by automating compliance enforcement, reducing manual intervention, and ensuring all EBS volumes are encrypted as per security standards.
