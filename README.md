# AWS Resource Listing Script

## Overview

This is a Bash script designed to automate the process of listing all resources in an AWS account for various services. The script supports multiple AWS services and allows users to specify the AWS region and service they are interested in.

## Supported Services

The script currently supports the following AWS services:

1. EC2 (Elastic Compute Cloud)
2. RDS (Relational Database Service)
3. S3 (Simple Storage Service)
4. CloudFront
5. VPC (Virtual Private Cloud)
6. IAM (Identity and Access Management)
7. Route53
8. CloudWatch
9. CloudFormation
10. Lambda
11. SNS (Simple Notification Service)
12. SQS (Simple Queue Service)
13. DynamoDB
14. EBS (Elastic Block Store)

## Prerequisites

Before running the script, ensure that the following prerequisites are met:

1. **AWS CLI Installed**: The script requires AWS CLI to be installed on your machine. You can install it by following the [official AWS CLI installation guide](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).

2. **AWS CLI Configured**: Ensure that the AWS CLI is properly configured with your credentials and default region. You can configure it using the command:
   ```bash
   aws configure


Usage
To run the script, use the following command:

bash
Copy code
./aws_resource_list.sh <aws_region> <aws_service>
Example
To list all EC2 instances in the us-east-1 region, run:

bash
Copy code
./aws_resource_list.sh us-east-1 ec2

