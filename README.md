# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* This project is based on a case study of a fictional healthcare company called Northstar Medical Group. The fast-growing company outsourced its identity lifecycle management workflow to a third-party managed service provider (MSP).

* Initially, the arrangement worked well. However, as the company grew, several issues began to emerge. The MSP did not have a role-based access control (RBAC) policy in place. Users were provisioned manually, with no standard naming convention, organizational unit (OU) structure, or consistent group memberships. These gaps created significant HIPAA compliance risks for a healthcare organization with more than 200 employees.

## Solution Overview
* I built and configured the NMG.com domain in Active Directory Windows Server. I designed a department-based organizational unit structure for four business units and implemented role-based access control using security groups aligned with each department. I provisioned 15 user accounts using standardized naming conventions, consistent attributes, and structured access assignments.  I also created and resolved a mock ticket where a user was provisioned the incorrect access level.
  
## Video Walkthrough
[![Watch the Active Directory RBAC Project Walkthrough](https://img.youtube.com/vi/-AWhPPAVX6U/hqdefault.jpg)](https://www.youtube.com/watch?v=-AWhPPAVX6U)

▶️ [Watch the full project walkthrough on YouTube](https://www.youtube.com/watch?v=-AWhPPAVX6U)

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
