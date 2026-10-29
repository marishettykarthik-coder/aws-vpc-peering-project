# AWS VPC Peering Project

## Project Overview

This project demonstrates how to establish private network connectivity between two Amazon Virtual Private Clouds (VPCs) using VPC Peering.

## Architecture

* VPC 1 CIDR: 10.10.0.0/16
* VPC 2 CIDR: 10.20.0.0/16
* VPC 1 EC2 private IP: 10.10.1.10
* VPC 2 EC2 private IP: 10.20.1.10

## AWS Services Used

* Amazon VPC
* Amazon EC2
* VPC Peering
* Subnets
* Route Tables
* Security Groups
* SSH

## Implementation Steps

1. Created two VPCs with non-overlapping CIDR ranges.
2. Created subnets and configured networking components.
3. Established a VPC peering connection.
4. Configured route tables for communication between VPCs.
5. Configured security groups.
6. Launched EC2 instances and configured SSH access.
7. Performed connectivity tests between the instances.

## Project Documentation

Refer to the `reports/` folder for the project report and supporting documentation.

## Connectivity Status

Update this section after completing the final connectivity tests.

