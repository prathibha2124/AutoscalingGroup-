# AutoscalingGroup-
#Create Auto Scaling Group of EC2 Instances for High Availability

Intro

Together, we will “Scale the Clouds” by following the steps to create an Auto Scaling Group (ASG) of Amazon EC2 Instances for high availability. We will literally be building a cloud infrastructure from ground up, so expect the use of many different AWS resources. Let’s get ready to build!
Don’t forget to delete all the resources created and configured after you are done following the steps of this article.

Background

Virtual Private Cloud (VPC):
Virtual Private Cloud is a service on AWS that offers a virtual private network, logically isolated from other virtual networks on the platform.

Subnet:
Subnets are a set of IP address ranges in your VPC.

Internet:
Internet Gateways enable AWS resources in public subnets with public IP addresses, to be able to connect to the internet.

Elastic Load Balancers:
Elastic Load Balancers automatically distribute incoming traffic across multiple targets such as Amazon EC2 Instances.

Route Table:
A Route Table contains a set of rules, called routes, that determine the direction of network traffic from subnets or an internet gateway.

Launch Template:
Launch Templates contain pre-configuration information used to launch resources such as Amazon EC2 Instance.

High Availability:
High availability refers to the elimination of single points of failure to enable infrastructures to continue operating, even if a component it depends on fails.

Use Case:

You are a Cloud Engineer for REX TECH, tasked to build a highly available Apache Web Servers cloud infrastructure. The infrastructure needs to have a minimum of 2 servers running at all times. Additionally, it must have the capability to scale out and increase to a maximum of 5 servers when the average CPU utilization increases to 50%.
Now, let’s get to building!
