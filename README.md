# Week 3 — Automating VPC setup with AWS CloudFormation

**Goal:** Define and deploy a custom VPC (public + private subnets, IGW, NAT, route tables, EC2) using CloudFormation.

## Architecture overview
- **VPC:** 10.0.0.0/16
- **Subnets:** 2 public + 2 private across two AZs
- **Gateways:** Internet Gateway for public, NAT Gateway for private
- **Routing:** Separate route tables for public and private
- **Compute:** EC2 instances in public and private subnets

- > See diagrams/vpc-architecture.png and screenshots for details.
