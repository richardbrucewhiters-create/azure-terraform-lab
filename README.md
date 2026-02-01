# Azure Live Production Mimic Terraform Lab

## Purpose
This lab demonstrates a production-style Azure infrastructure deployed entirely with Terraform.

## Architecture
- Azure VNet with segmented subnets
- Linux compute tier
- Remote Terraform state
- Modular Terraform design

## Deployment Steps
1. Create Azure Storage Account for Terraform state
2. Run `terraform init`
3. Run `terraform plan`
4. Run `terraform apply`
