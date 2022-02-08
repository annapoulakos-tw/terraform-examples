# Conditional Module

Allows you to run a module only if a specified condition has been met, in this case as a feature toggle.

## Setup

* Requires `terraform`
* Run `terraform init` from this directory

## Usage

**Enable module**
```bash
terraform plan -var-file enable.tfvars
```

**Disable module**
```bash
terraform plan -var-file disable.tfvars
```
