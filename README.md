# Static Website Deployment on AWS S3 using Terraform

This project deploys a static websute on a public Amazon S3 bucket using Terraform.

---

## Prerequisite

Authenticate your IAM user with the [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) using your Access Key

## Steps
1. Clone the repository
2. Create a `terraform.tfvars` file with a variable `bucketname` for the name of your bucket
3. Run `terraform init`
4. Run `terraform plan`
5. Run `terraform apply -auto-approve`

## Cleanup
When you're done, clean it up with `terraform destroy`.