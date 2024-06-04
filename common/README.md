# Overview
- Create AWS resources for common use cases.

# File List
- 01_vpc.yaml: Used to create VPC.
- 02_igw.yaml: Used to create an Internet Gateway and attach it to an existing VPC.
- 03_rtb.yaml: Used to create public and private route tables.
- 04_subnets.yaml: Used to create public and private subnets and associate them with the respective route tables.

# How to Use
1. Run the CloudFormation templates in AWS Management Console or via AWS CLI.
2. Deployment sequence:
    1. 01_vpc.yaml
    2. 02_igw.yaml
    3. 03_rtb.yaml
    4. 04_subnets.yaml
4. Run the templates using the CloudFormation console or AWS CLI and provide necessary parameters during the deployment process.

**Notes:**
- Ensure that you have appropriate IAM permissions before deploying the templates.
- Review each parameter and resource definition carefully to ensure they meet your requirements before deployment.
- After deployment, validate the created resources to ensure they meet expectations.
