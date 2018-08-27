* [cluster-of-web-servers](./cluster-of-web-servers): Deploy a cluster of EC2 Instances in an Auto Scaling Group (ASG)
  and an Elastic Load Balancer (ELB). The ELB listens on port 443 and distributes load across the EC2 Instances, each
  of which runs the same "Hello, World" web server.

## Quick start

**Note**: These examples deploy resources into your AWS account. Although all the resources should fall under the
[AWS Free Tier](https://aws.amazon.com/free/), it is not our responsibility if you are charged money for this.

1. Install [Terraform](https://www.terraform.io/).
1. Set your AWS credentials as the environment variables `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.
1. `cd` into one of the two example folders.
1. Run `terraform plan`.
1. If the plan looks good, run `terraform apply`.


