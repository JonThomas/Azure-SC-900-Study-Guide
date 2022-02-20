# Describe what identity governance is

[Describe what identity governance is](https://docs.microsoft.com/en-us/learn/modules/describe-identity-protection-governance-capabilities/2-describe-identity-governance)

Identity governance is about balancing identity security with user productivity in a way that can be justified and audited. 

Azure AD identity governance enables the following in organizations:
* Govern the identity lifecycle
* Govern access lifecycle
* Secure privileged access for administration

Azure AD identity governance help organizations answer the following questions:
* Which users have access to which resources
* What are those users doing with the access
* Are there effective organizational controls for managing access
* Can auditors verify that the controls are working

## Govern the identity lifecycle
* Employee **joins** the company: Give access
* Employee **moves**: Change access
* Employee **leaves**: Remove access

Azure AD Premium offers integration with cloud-based HR systems, in case users aren't updated in Azure AD directly.

Azure AD Premium also includes **Microsoft Identity Manager**, which can import records from on-premises HR systems such as SAP and Oracle.

## Govern access lifecycle
* Much like the identity lifecycle. 
* Access can be automated using Azure AD dynamic groups.
    * Group membership is automatically assigned, by using attributes on the user.

## Privileged access lifecycle for administrators
* Monitoring privileged access is important!
* See [Privileged Access Management (PIM)](43-Describe%20the%20capabilities%20of%20PIM.md), which helps minimize the number of people who have access to resources

[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)