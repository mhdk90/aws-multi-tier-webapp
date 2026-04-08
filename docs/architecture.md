# Architecture

```mermaid
flowchart LR
  U[Users] --> CF[CloudFront]
  CF --> ALB[Application Load Balancer]
  ALB --> EC2[EC2 Web Tier]
  EC2 --> RDS[(RDS Multi-AZ)]
