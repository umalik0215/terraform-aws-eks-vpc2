# terraform-aws-eks-vpc
Provision AWS VPC and EKS clusters using reusable Terraform modules. Includes Sentinel policy for governance.

## Features
- VPC with public/private subnets
- EKS cluster (v1.29) with managed node groups
- Sentinel policy enforcing mandatory tags

## Usage
```bash
terraform init
terraform apply -var 'region=us-east-1'
