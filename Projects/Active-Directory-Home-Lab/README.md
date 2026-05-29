# Active Directory Home Lab Infrastructure

## Project Overview

This project demonstrates the deployment and administration of a Windows Server 2022 Active Directory environment within a home lab. The objective was to simulate a real world enterprise identity infrastructure by installing Active Directory Domain Services (AD DS), configuring DNS, creating organizational units, managing users and groups, and preparing the environment for workstation domain joins.

## Environment

## Virtual Machines

| Machine |      Operating System |       Purpose |
|---------------|-----------------------|----------------|
| DC10 | Windows Server 2022 | Domain Controller |
| WorkLab2 | Windows 10 | Client Workstation | 

## Domain Information

- Domain Name: mydomain.local
- Domain Controller IP: 192.168.1.10
- DNS Server: 192.168.1.10

# Step 1 Install Windows Server 2022

A Windows Server 2022 virtual machine was deployed using Oracle VirtualBox.

## Tasks Performed

- Created new VM
- Allocated memory and storage
- Installed Windows Server 2022
- Configured administrator password
  
