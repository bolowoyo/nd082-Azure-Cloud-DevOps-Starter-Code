# Azure Infrastructure Operations Project: Deploying a scalable IaaS web server in Azure

### Introduction
For this project, you will write a Packer template and a Terraform template to deploy a customizable, scalable web server in Azure.

### Getting Started
1. Clone this repository

2. Create your infrastructure as code

3. Update this README to reflect how someone would use your code.

### Dependencies
1. Create an [Azure Account](https://portal.azure.com) 
2. Install the [Azure command line interface](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
3. Install [Packer](https://www.packer.io/downloads)
4. Install [Terraform](https://www.terraform.io/downloads.html)

### Instructions
**Your words here**

Creating the Packer File

- Please check server.json to see final file.
- Run packer build server.json to build the packer image
- 


The terraform file creates the following resources:

- Create a virtual network and subnet in the Resource Group ( The resource group, i previously created. Made the reference in the tf file)
- Creates a network security group, with some explicitly defined allow and deny rules
- Creates a network interface
- Creates a public IP
- Creates a load balancer
- Creates a virtual machine availability set
- Creates virtual machines.
-   Referenced the packer image in my resource group
-   Creates managed disks for my virtual machines

- Virtual machine count can be modified by changing the vm_count variable in the variables.tf file
- 

### Output
**Your words here**

