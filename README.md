# Terraform AWS Project

This project provisions infrastructure on AWS using Terraform.

## Resources Created

- VPC with 2 public subnets
- Internet Gateway and Route Tables
- Security Group for SSH/HTTP
- 2 EC2 Instances with user-data scripts
- Application Load Balancer
- Public S3 Bucket


## How to Run

# Run:
   - terraform init
   - terraform plan
   - terraform apply

## Notes

- `.tfstate` files are excluded using `.gitignore`
- Instances are deployed across 2 AZs with ALB
- User-data script installs a basic web server

