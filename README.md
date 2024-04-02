#Azure Infrastructure Deployment with Terraform


##Overview

This repository contains terraform scripts for deploying a robust azure infrastructure, as depicted in the accompanying architectural diagram.  the setup includes variety of of services and resources, ensuring a secure and efficient cloud environment

##Architecture

the architecture comprises the following componets
-**Storage account** for persistent data storage
-**Key vault** to manage secrets and keys securely
**-Azure baston** provides secure rdp and ssh connectivity to virtual machines
**Management services** hosts domain-related services
**Cluster nodes**a set of nodes for handling worloads, each with attached data disks

##Prerequisites

-Azure subscription
-Terraform installed on your loacl machine

##usage 

-Clone the repository to your local machine
-Naviagate to the terraform script directory
-Initialize terraform with 'terraform init'
-Apply the terraform configuration with 'terraform apply'


#Contributions 

Contributions to this project are welcome, please fork the repository and submit a pull request with changes 
