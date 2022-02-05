# terraform-demo

I am using the latest version of terraform.

+ { % terraform -v
Terraform v1.1.4
on darwin_amd64
+ provider registry.terraform.io/hashicorp/aws v3.74.0}#

I have tried implementing the sections from the lecture as per the serial. You can refer to below branches for detailed files and instructions.

> + DefRT+SG_18_19 branch include the main.tf file which is for SECTION:18 and SECTION:19.
  This includes the demonstration of exercise by using the default component in the HCL such and Default Route and creating the Security group for Firewall         configuration.
  
> + EC2_AMI_20_21   branch include the main.tf file which is for SECTION:20 and SECTION:21.
  This includes the demonstration of exercise by creating the EC2 Instance and defining its pre-requisite within main.tf such as Latest Amazon Machine Image, applying filter on the basis of type of Image for creating the server.
  
> + Create_SSH_key&_script  : This is from Section 22 to 24
  This gives the detailed view on how to create a SSH key pair which can be used to login without password for enhanced security. Also, we utilise the feature of USER DATA feature from AWS and integrating it with Terraform by simply passing a script for various benefits.
  
> + feature_modules : this branch hold the relevant files which were in use while demonstrating the Module section and its feature.

> + vpc_module_3.11.5: under this section we have made use of existing module of VPC directly from the provider i.e terraform
Used latest module of VPC i.e 3.11.5, so our demostration is still compatible and valid with the module which is shown in video. (2.66.0)

> + remote_state : Demonstarted how it retrieves state data from a Terraform backend or source. 

