# About

------------

This project represents Infrastructure as Code (IaC) for deploying Azure Virtual Machines using Terraform. It utilizes a module that enables deploying multiple machines while reusing the same configuration.
## Module "vm":
This module contains the necessary resources for deploying a single virtual machine, including:

- Azure Public IP.
- Azure Network Interface.
- Azure Network Security Group.
- Azure Network Interface Security Group Association.
- Azure Network Security Rule.
- Azure Virtual Machine.


------------

## Main

This module contains the resources required for a group of virtual machines, including:

- Azure Resource Group.
- Azure Virtual Network.
- Azure Subnet.
- "vm" module (for deploying the virtual machines).

#### Finally, we proceed to create it with the Terraform commands.
    terraform init

Initializes the Terraform environment.

    terraform validate
	
Validates the syntax and configuration of Terraform files.

    terraform plan

 Generates a plan of infrastructure changes.

    terraform fmt
Applies consistent formatting to Terraform code.

    terraform apply

Applies the changes defined in Terraform files.


### VM Created.
![image](https://github.com/Sebastianavia/VM-modular-Terraform-AZ/assets/71205906/b0dd5fe9-8784-46aa-865f-cf12546c7748)







