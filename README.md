# Terraform AWS Provisioning

## Objective

This project demonstrates Infrastructure as Code (IaC) using Terraform to provision basic AWS infrastructure.

## AWS Resources

- VPC
- Public Subnet
- Security Group
- Amazon S3 Bucket

## Project Structure

- main.tf
- variables.tf
- terraform.tfvars
- outputs.tf

## Terraform Commands

Initialize Terraform

```bash
terraform init
```

Validate Configuration

```bash
terraform validate
```

Preview Changes

```bash
terraform plan
```

Deploy Infrastructure

```bash
terraform apply
```

Destroy Infrastructure

```bash
terraform destroy
```

## Infrastructure Diagram

Internet
↓
VPC
↓
Public Subnet
↓
Security Group
↓
EC2 (future deployment)
↓
S3 Bucket

## What I Learned

- Terraform fundamentals
- AWS networking basics
- Infrastructure as Code (IaC)
- Resource provisioning
- Terraform configuration syntax

## Challenges Faced

Understanding Terraform providers, AWS networking resources, and Infrastructure as Code concepts was initially challenging. Through creating Terraform configuration files and learning resource relationships, I gained a better understanding of automated infrastructure provisioning.
