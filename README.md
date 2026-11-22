
# Project 7: CI Validation for Terraform

## Objective
The objective of this project is to automate Terraform code validation using GitHub Actions.

## Tools Used
- Terraform
- Git
- GitHub
- GitHub Actions
- Ubuntu Linux

## Implementation
1. Created a separate project directory named `project-7`.
2. Created a Terraform configuration file named `main.tf`.
3. Created a GitHub Actions workflow inside `.github/workflows/terraform.yml`.
4. Configured Terraform Format Check using `terraform fmt -check -recursive`.
5. Configured Terraform initialization using `terraform init -backend=false`.
6. Configured Terraform validation using `terraform validate`.
7. Initialized a Git repository and committed the project files.
8. Created a GitHub repository named `terraform-ci-validation`.
9. Configured GitHub Actions to run automatically on push and pull requests.

## GitHub Repository
https://github.com/anuugyaag/terraform-ci-validation

![Terraform CI](https://github.com/anuugyaag/terraform-ci-validation/actions/workflows/terraform.yml/badge.svg)

## Conclusion
This project demonstrates how GitHub Actions can automate Terraform formatting and validation checks, helping maintain code quality and identify configuration errors.




