# Multi-Tier Web Application on AWS

## Overview
This project demonstrates a multi-tier AWS architecture built with CloudFormation.

## Goal
Design a scalable and highly available web application foundation using networking, compute, load balancing, and database components.

## Current Scope
- VPC
- Public subnets
- Internet gateway
- Route table
- Security groups
- EC2 web server

## Planned Architecture
- Application Load Balancer
- Auto Scaling Group
- Private subnets
- RDS Multi-AZ
- CloudFront

## Repository Structure
- `cloudformation/` – CloudFormation templates
- `docs/` – architecture and deployment notes

## Deployment Notes
This repository is a starter foundation. Environment-specific values such as AMI IDs, SSH CIDR ranges, and database settings should be passed as parameters.

## Security Notes
- No secrets are stored in this repository
- SSH access should be restricted to a narrow admin CIDR
- Backend resources should not be exposed directly to the internet

## Roadmap
- Split the template into smaller files
- Add architecture diagram
- Add deployment and cleanup commands
- Add CI workflow

## What I Learned
- How to structure AWS infrastructure in CloudFormation YAML
- How to separate networking and application layers
- How to document cloud projects clearly for GitHub and CV use
