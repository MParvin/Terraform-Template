# Terraform Code Template

It's a template for creating a new Terraform project with best practices and modular structure.

## Features

- Modular structure with separate modules for each component
- Separate environments for production and staging
- Customizable variables for each environment
- Built-in error handling and logging
- Integration with popular CI/CD tools

## Prerequisites

- Terraform installed on your machine
- Basic knowledge of Terraform and its syntax
- Access to the cloud provider you want to use (e.g., AWS, GCP, etc.)

## Usage

1. Clone this repository
1. Create a new directory for your project
1. Copy the `terraform` directory from this repository into your project directory
1. Customize the `main.tf` file to match your infrastructure requirements
1. Run `terraform init` to initialize the Terraform configuration
1. Run `terraform plan` to view the planned changes
1. Run `terraform apply` to apply the changes

## Structure

- `prod`: Production environment
- `stage`: Staging environment
- `modules`: Custom modules directory
- `modules/network`: Network module

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Thanks

Thanks to [@antonbabenko](https://github.com/antonbabenko) for the [Terraform Best Practices free ebook](https://github.com/antonbabenko/terraform-best-practices) that served as a starting point for this template.