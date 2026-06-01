# File Server & Access Management

## Project Overview

This project demonstrates the deployment and management of shared network resources within a Windows Server Active Directory environment. The objective was to create departmental file shares, configure access permissions, implement Role Based Access Control (RBAC), and verify secure access using Active Directory security groups.

## Environment

### Infrastructure

| Component |	Description |
|----------------|-----------------|
| Domain Controller	| DC10 |
| Operating System	| Windows Server 2022 |
| Domain	| mydomain.local |
| Client Workstation |	WorkLab2 |
| Active Directory |	Configured |


## Step 1 Create Shared Folder

A shared folder was created to simulate departmental file storage.

### Folder Created

C:\HR_Files

### Purpose

The folder was created to provide centralized file storage for HR users.

### Screenshot

## Step 2 Configure Network Share

The folder was shared on the network.

### Tasks Performed

- Opened Folder Properties
- Selected Sharing tab
- Opened Advanced Sharing
- Enabled Share this folder
- Assigned share name

### Share Name

HR_Files

### Screenshot

### Screenshot


## Step 3 Configure Share Permissions

Share permissions were configured to control network level access.

### Tasks Performed

- Opened Share Permissions
- Reviewed existing permissions
- Configured access for authorized users

### Purpose

Share permissions determine who can access the shared folder across the network.

### Screenshot



