# Basics

## What is it?
Infrastructure as code tool from Hashicorp.

Basic process to deploy infrastructure with Terraform:
1. **Scope** - Identify the infrastructure for your project.
2. **Author** - Write the configuration for your infrastructure.
3. **Initialize** - Install the plugins Terraform needs to manage the infrastructure.
4. **Plan** - Preview the changes Terraform will make to match your configuration.
5. **Apply** - Make the planned changes.

## Installation
Install via Homebrew
``` shell
brew tap hashicorp/tap
brew install hashicorp/tap/terraform

# To upgrade terraform
brew update
brew upgrade hashicorp/tap/terraform

# To validate install work
terraform -help
```

To enable auto-complete
``` shell
terraform -install-autocomplete
```
