# EKS Setup with Terraform

## Setup S3 bucket as terraform backend

- Make sure you are in the `eks-install` folder of the project.
- Switch to the backend folder 
```bash
cd backend
```
- Create S3 bucket and Dyanmodb
```bash
terraform init
terraform plan
terraform apply
```

## Install EKS with VPC

- Make sure you are in the `eks-install` folder of the project.

- Create eks with vpc
```bash
terraform init
terraform plan
terraform apply
```