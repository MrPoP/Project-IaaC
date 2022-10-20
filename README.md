# Project-IaaC
this project about Deploy a high-availability web app using CloudFormation
http://proje-webap-1ks661rw6ldp6-2121327639.us-east-1.elb.amazonaws.com/ this is the link for website 
Project Overview

Suppose company is creating an Instagram clone like application. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket. Now the task is to deploy the application, along with the necessary supporting software into its matching infrastructure. This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

Project Files

    /cloudformation-stacks:
        Network-Parameters.json: Parameters file for network cloudformation stack.
        NetworkInfrastructureProject.yml: CloudFormation template for creating networking resources for this project.
        Servers-Paramteres.json: Parameters file for servers cloud formation stack.
        ServersProject.yml: CloudFormation template for creating servers for this project.

#Project Setup

    To create networking resources using cloudformation template, run the below command. After exceuting it these are the resources created:

    VPC
    Subnets
    Route Tables
    Routes
    Internet Gateway
    NAT Gateways