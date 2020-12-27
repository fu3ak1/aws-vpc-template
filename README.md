# aws-vpc-template
Some common vpc templates (IaC)

## Simple VPC

[CloudFormation Template](./cfn/00-vpc.yml)

* 2 Public Subnets and 2 Private Subets
* Intenet Gateway

[](./images/00-vpc.dio.svg)

## VPC with NAT Gateway

[CloudFormation Template](./cfn/01-vpc-natgw.yml)

* 2 Public Subnets and 2 Private Subets
* Intenet Gateway
* Nat Gateway

[](./images/01-vpc-natgw.dio.svg)

## VPC with FLow Logs (S3)

[CloudFormation Template](./cfn/02-vpc-s3flowlogs.yml)

* 2 Public Subnets and 2 Private Subets
* Intenet Gateway
* VPC Flow Logs with S3 Bucket

[](./images/02-vpc-s3flowlogs.dio.svg)

## VPC with Endpoint for S3

[CloudFormation Template](./cfn/03-vpc-s3endpoint.yml)

* 2 Public Subnets and 2 Private Subets
* Intenet Gateway
* VPC Endpoint for S3

[](./images/03-vpc-s3endpoint.dio.svg)

## VPC with all options so far

[CloudFormation Template](./cfn/04-vpc-alloptions.yml)

* 2 Public Subnets and 2 Private Subets
* Intenet Gateway
* Nat Gateway
* VPC Flow Logs with S3 Bucket
* VPC Endpoint for S3

[](./images/04-vpc-alloptions.dio.svg)

## VPC with 6 subnets

[CloudFormation Template](./cfn/05-vpc-6subnets.yml)

* 2 Public Subnets and 4 Private Subets
* Intenet Gateway

[](./images/05-vpc-6subnets.dio.svg)