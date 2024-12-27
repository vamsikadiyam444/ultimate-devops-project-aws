# Install and Configure Terraform

## Install

Follow the official terraform installation guide
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

## Verify Installation

`terraform --version`

## Configure Terraform for AWS

- Go to the AWS Console with your IAM User, To the top right, Click on the User dropdown, Click on Security credentials.
- Go to Access Keys, Click on Create access key.
- Copy Access key and Secret access key.

Run AWS Configure to update AWS config and credentails files.

```bash
aws configure
```

Once done, Terraform can authenticate with AWS using these credentails. 

There are multiple other ways of configuring AWS credentails with Terraform. Please refer the below link if you are interested.
https://registry.terraform.io/providers/hashicorp/aws/latest/docs#authentication-and-configuration

