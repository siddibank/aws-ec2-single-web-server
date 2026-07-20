# aws-ec2-single-web-server
Single-server web hosting on AWS EC2 using Apache and the default VPC

# Overview

This project is the first in a hands-on AWS series aimed at building practical cloud engineering skills. The goal was simple: understand how a web application runs on a single server by launching an EC2 instance, installing a web server, and serving a static HTML page over the public internet.

No load balancers, no auto-scaling, no managed services — just one server doing all the work. This is the foundation every other AWS architecture builds on top of.

# What I Built

A single EC2 instance running Apache HTTP Server (httpd), serving a static HTML page accessible via the instance's public IP address, using AWS's default VPC networking.

# AWS Services Used

- Amazon EC2
- Amazon VPC (Default VPC)
- Security Groups
- Internet Gateway

## Architecture Diagram

![Architecture](architecture/Single-EC2-web-server-architecture-diagram.png)
