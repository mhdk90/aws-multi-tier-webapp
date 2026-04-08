# Multi-Tier Web Application on AWS

## Overview
This project demonstrates a multi-tier AWS architecture using CloudFormation YAML.

## Goal
Build a scalable and highly available web application foundation with networking, compute, and database components.

## Current Scope
- VPC
- Public subnets
- Internet gateway
- Route table
- Security groups
- EC2 web server

## Planned Next Steps
- Add Application Load Balancer
- Add Auto Scaling Group
- Add private subnets
- Add RDS Multi-AZ database
- Add CloudFront

## Repository Structure
- `cloudformation/` – infrastructure templates
- `docs/` – notes and architecture explanations

## Security Notes
- No secrets are stored in this repository
- Environment-specific values should be passed as parameters

## What I Learned
- How to structure AWS infrastructure with YAML
- How to separate networking and application layers
- How to document cloud projects for GitHub and CV use
