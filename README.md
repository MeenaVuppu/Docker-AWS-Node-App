# **DevOps_Learnings**

## *This repo contains practical implementations of my learnings in DevOps with AWS*

**Application stack**:

Backend- Node js-express js application with Mondgo db as database

**Docker**:

Pulled Mongo and Mongo express images from docker hub. Integrated the application with Mongo db

**AWS**:

Created a VPC with Public and Private subnets. 
Provisioned an EC2 instance in each of those subnets. 
Made a connection to the private EC2 instance through the public EC2 instance.
Uploaded the app image I build with my code into the aws public ec2 instance using WinSCP file transfering, from there to my private instance.
Now installed docker in my private instance and executed the api
