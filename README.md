# tf_vpc
Terrform basic vpc module



# AWS VPC module for Terraform 
A lightweight VPC module for Terraform. 
## Usage
 module "vpc_basic" {
    source = "github.com/rneighborsphone/tf_vpc" 
    name = "vpc_name" 
    cidr = "10.0.0.0/16" 
    public_subnet = "10.0.1.0/ 24" 
} 

See ` interface.tf ` for additional configurable variables. 


## License MIT
