# Hybrid Identity & Access Management Lab

> Hands-on IAM lab simulating a hybrid identity environment using on-premises Active Directory and Microsoft Entra ID.

![Architecture Diagram](Architecture_Diagram.png)

## Overview

This project is a hands-on Identity and Access Management (IAM) lab built to simulate common enterprise identity operations across an on-premises Active Directory environment and Microsoft Entra ID.

The lab focuses on identity lifecycle management, access control, authentication, provisioning, synchronization, and IAM troubleshooting.

## Environment

- **Windows Server 2025** — Active Directory Domain Services
- **Microsoft Entra ID** — Cloud identity platform
- **Microsoft Entra Cloud Sync** — Hybrid identity synchronization
- **Active Directory Users & Computers** — User and group administration
- **Group Policy** — Centralized access and endpoint management
- **pfSense** — Network gateway and DNS infrastructure

## Key IAM Activities

- Created and managed Active Directory users, groups, and organizational units
- Implemented role-based access and permission management
- Configured Microsoft Entra Cloud Sync for hybrid identity synchronization
- Validated user provisioning from Active Directory to Microsoft Entra ID
- Tested on-demand provisioning and synchronization
- Practiced identity lifecycle workflows including joiner, mover, and leaver scenarios
- Troubleshot authentication, provisioning, synchronization, and access issues

## Architecture

The lab follows a hybrid identity model:

**On-Premises Active Directory → Microsoft Entra Cloud Sync → Microsoft Entra ID**

Users and groups are managed in the on-premises Active Directory environment and synchronized to Microsoft Entra ID for cloud identity and access management.

## Project Status

🚧 **Documentation in progress**

The lab is actively being expanded with additional IAM scenarios, access-management workflows, and troubleshooting exercises.

## Skills Demonstrated

`Identity & Access Management` · `Active Directory` · `Microsoft Entra ID` · `Cloud Sync` · `RBAC` · `MFA` · `User Provisioning` · `Identity Lifecycle Management` · `Group Policy` · `IAM Troubleshooting`
