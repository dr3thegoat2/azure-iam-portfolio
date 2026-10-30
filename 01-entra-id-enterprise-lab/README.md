# Microsoft Entra ID — Enterprise IAM Lab

## Project Overview

This project simulates identity and access management operations for WareTech Solutions, a fictional company with five departments.

The lab uses Microsoft Entra ID to demonstrate enterprise identity administration, security group management, authentication security, and access control.

## Business Problem

Organizations need a centralized way to manage employee identities and permissions. Managing access individually can introduce administrative overhead, inconsistent permissions, and security risks.

## Project Objectives

- Establish a Microsoft Entra ID lab environment.
- Verify administrator permissions.
- Review Security Defaults and MFA configuration.
- Create department-based security groups.
- Provision fictional employee identities.
- Assign and validate group memberships.
- Apply least-privilege principles.

## Technologies Used

- Microsoft Entra ID
- Microsoft Azure Portal
- Microsoft Graph PowerShell (planned)
- GitHub

## Implementation Progress

| Task | Status |
|---|---|
| Entra tenant established | Completed |
| Global Administrator role verified | Completed |
| Security Defaults verified | Completed |
| Administrator MFA registration | Pending |
| IT security group created | Completed |
| Remaining department groups | In progress |
| Employee provisioning | Not started |
| Access validation | Not started |

## Security Considerations

The lab uses fictional employee identities and sanitized documentation. Sensitive authentication details and tenant identifiers are excluded from the public repository.

## Evidence

Screenshots, scripts, and test results will be added as implementation progresses.

## Lessons Learned

This section will document IAM concepts, troubleshooting experiences, and security decisions encountered during the project.

## Implementation Evidence

The following screenshots document the configuration and validation of the WareTech Solutions Microsoft Entra ID IAM lab.

| Evidence | Description |
|---|---|
| [01 - Administrator Role](screenshots/01-global-admin-role.png) | Verification of the lab administrator's Global Administrator role |
| [02 - Security Defaults](screenshots/02-security-defaults.png) | Confirmation that Security Defaults are enabled |
| [03 - IT Security Group](screenshots/03-it-security-group.png) | Creation of the IT department security group |
| [04 - Department Security Groups](screenshots/04-all-security-groups.png) | Five department-based security groups |
| [05 - Employee Provisioning](screenshots/05-employee-account-created.png) | Provisioning of a fictional employee identity |
| [06 - IT Group Membership](screenshots/06-it-group-membership.png) | IT employee group membership validation |
| [07 - Security Group Membership](screenshots/07-security-user-membership.png) | Security employee group membership validation |
| [08 - Administrative Role Audit](screenshots/08-security-user-role-audit.png) | Review of a security employee's directory role assignments |

## Key Skills Demonstrated

- Microsoft Entra ID user provisioning
- Security group creation and membership administration
- Department-based identity organization
- Identity security configuration
- Administrative role assignment review
- Least-privilege principles
- IAM documentation and evidence collection

## Project Limitations

This lab demonstrates identity provisioning, group membership management, and directory role reviews. Application-level authorization, automated identity lifecycle management, and broader access certification are separate project phases.
