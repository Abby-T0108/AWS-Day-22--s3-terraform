# AWS-Day-22--s3-terraform
              Overview

A fully automated deployment of a responsive static website to AWS S3 using Terraform. 
This project demonstrates infrastructure as code, secure public hosting and a clean DevOps workflow suitable for production-ready portfolios.

Live demo: update with your S3 website endpoint or custom domain

           What this demonstrates
1. Deploying AWS infrastructure with Terraform
2. Configuring S3 for static website hosting
3. Applying least-privilege IAM policies for public read-only access
4. Building a responsive HTML/CSS website
5. Documenting a reproducible workflow end-to-end

          Technologies

1. AWS S3 (static website hosting)
2. Terraform ~> 5.0
3. HTML5/CSS3
4. Visual Studio Code
5. AWS CLI, PowerShell or Bash

         Architecture
Developer (local) → Terraform (IaC) → AWS S3 (Static Website)

1. AWS account with permissions for S3 and IAM
2. Terraform installed (terraform --version)
3. AWS CLI configured (aws configure) or use a named profile

          Results

1. End-to-end automated deploy in minutes
2. Reproducible IaC with single-command teardown
3. Clear, auditable security configuration
4. Responsive UI delivered over S3 website hosting
