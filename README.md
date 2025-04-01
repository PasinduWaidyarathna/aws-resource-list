# AWS Resource List Script

## Description
This Bash script automates listing AWS resources in a specified region. It supports services like EC2, RDS, S3, Lambda, and more, ensuring that the AWS CLI is installed and configured before execution.

## Features
- Lists resources for various AWS services, including:
  - EC2 (Instances)
  - RDS (Databases)
  - S3 (Buckets)
  - CloudFront (Distributions)
  - VPC (Virtual Private Cloud)
  - IAM (Users)
  - Route53 (Hosted Zones)
  - CloudWatch (Alarms)
  - CloudFormation (Stacks)
  - Lambda (Functions)
  - SNS (Topics)
  - SQS (Queues)
  - DynamoDB (Tables)
  - EBS (Volumes)
- Checks if AWS CLI is installed and properly configured.
- Allows users to specify the AWS region and service for resource listing.

## Usage
Run the script with the following command:
```bash
./aws_resource_list.sh <aws_region> <aws_service>
```

### Example:
To list EC2 instances in the us-east-1 region:
```bash
./aws_resource_list.sh us-east-1 ec2
```

### Supported Services:
- **ec2**: List EC2 instances.
- **rds**: List RDS instances.
- **s3**: List S3 buckets.
- **cloudfront**: List CloudFront distributions.
- **vpc**: List VPCs.
- **iam**: List IAM users.
- **route53**: List Route53 hosted zones.
- **cloudwatch**: List CloudWatch alarms.
- **cloudformation**: List CloudFormation stacks.
- **lambda**: List Lambda functions.
- **sns**: List SNS topics.
- **sqs**: List SQS queues.
- **dynamodb**: List DynamoDB tables.
- **ebs**: List EBS volumes.

## Prerequisites
1. **AWS CLI**: Ensure that the AWS CLI is installed on your system.
   - [Install the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

2. **AWS Configuration**: Ensure that the AWS CLI is configured with your credentials.
   ```bash
   aws configure
   ```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/PasinduWaidyarathna/aws-resource-list.git
   ```

2. Navigate to the project directory:
   ```bash
   cd aws_resource_list
   ```

3. Make the script executable:
   ```bash
   chmod +x aws_resource_list.sh
   ```

## Contributing
Contributions are welcome! Feel free to fork the repository, submit issues, and create pull requests.

## Author
- **Pasindu Waidyarathna**
