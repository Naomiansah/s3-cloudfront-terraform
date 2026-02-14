# S3 + CloudFront Static Website Deployment (Terraform)

This project deploys a secure static website using:

- Amazon S3 (private bucket)
- CloudFront distribution
- Origin Access Control (OAC)
- IAM bucket policy
- Terraform Infrastructure as Code

## Why this project?

To demonstrate hands-on cloud engineering skills including:
- Secure S3 configuration
- CloudFront origin restriction
- Infrastructure automation
- State management best practices

## Architecture

S3 (private) → CloudFront (OAC) → Internet


Note: Infrastructure can be recreated at any time using:

terraform init
terraform apply
