# Terraform-IaC
A collection of Infrastructure as Code (IaC) scripts using Terraform to provision various AWS resources. 


# Getting Started
Prerequisites
- **Terraform**: [Terraform](https://www.terraform.io/ "Terraform")  
- **AWS CLI**: [AWS Cli](https://aws.amazon.com/cli/ "AWS Cli")  

# How to Use
To deploy a specific resource, navigate to its respective folder and execute Terraform commands.

### Steps

1. **Clone the repository**:
   ```sh
   git clone  https://github.com/CyrilBaah/Terraform-IaC.git
   cd <the-respective-folder>
   ```

2. **Navigate to a Specific Folder**:
   ```sh
   cd <the-respective-folder>
   ```

3. **Initialize Terraform**:
   ```sh
   terraform init
   ```

4. **Plan Deployment**:
   ```sh
   terraform plan
   ```

5. **Apply changes**:
   ```sh
   terraform apply
   ```

5. **Destroy Infrastructure (If Needed)**:
If you want to delete the deployed resources:
   ```sh
   terraform destroy
   ```

Confirm with **yes** when prompted.


## Stacks

| Resouce                | Description                                                                             |
|------------------------|-----------------------------------------------------------------------------------------|
| EC2 Instance           |Deploys an EC2 instance with configurable instance type, security groups                 |


# Contributing
We welcome contributions! Feel free to fork this repository, make improvements, and submit a pull request.

