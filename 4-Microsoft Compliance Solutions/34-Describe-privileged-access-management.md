# Describe privileged access management

[Describe privileged access management](https://docs.microsoft.com/en-us/learn/modules/describe-insider-risk-capabilities-microsoft-365/5-describe-privileged-access-management)

Privileged access management (PAM) allows granular access control over privileged admin tasks in Microsoft 365.

PAM is configured and monitored in the *Office 365 Admin Center*??

## Zero standing access:
* Admins who need privileged access must request permissions
* Admins will receive only the level of access they need
* Admins will receive access just when they need it
* Admins will receive just-enough access

## Workflow:
1. Configure privileged access policy, scoped at individual **tasks**
1. Admin requests access - access request is sent to Microsft 365, and recorded in the Security and Compliance Center logs
1. Access approval 
    * Approval or denial is emailed to user
    * Approval can be set up to be manually or automatically approved   
1. Access processing - activity is logged in the Security and Compliance Center.

## Microsoft 365 PAM vs [Azure AD PIM](../2-Microsoft-Identity-and-Access-Management-Solutions/43-Describe-the-capabilities-of-PIM.md)
* PAM: Scoped at the task level
* PIM: Protection at the role level
* PIM: Allows managing access for AD roles and role groups

[Return to Microsoft Compliance Solutions](README.md)

[Return to Table of Contents](../README.md)