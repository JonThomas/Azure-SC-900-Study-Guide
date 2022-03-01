# Describe what conditional access is

[Describe what conditional access is](https://docs.microsoft.com/en-us/learn/modules/explore-access-management-capabilities/2-describe-conditional-access-its-benefits)

A Conditional Access policy automatically gives or denies access to resources (apps and data), only after having analysed signals including user, location, device, application, and risk to .

Conditional Access policy is an Azure Premium feature

Conditional access policies use _if then_ statements, with signals to determine wheter to grant access, require more information, or block access:  

## Signals
* User or group membership
* Location (IP ranges)
* Device
* Application
* Real-time sign-in risk detection, using [Azure AD Identity Protection](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/1-Manage%20identity%20and%20access/25-Configure%20Azure%20AD%20Identity%20Protection.md): Risky sign-in behavior - the probability that a given sign-in, or authentication request, isn't authorized by the identity owner - is identified using leaked credentials, atypical tracel, etc.
* Cloud applications or actions can be explicitly included/ excluded from conditional access signals

## Access Controls
Based on signals, the following access controls can be applied:
* Block or grant access to specific members, groups or guests
* Require extra conditions:
    * MfA
    * Device compliency
    * Approved app
    * Password change
    * ...
* Enable limited access
    * Block copy/ paste
    * Block download
    * ...

See also [Endpoint security with Intune](../3-Microsoft Security Solutions/62-Describe-endpoint-security-with-Intune.md), which uses conditional acccess enforce which devices and apps can access corporate resources 

See also [Conditional access in the AZ-500 study guide](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/1-Manage%20identity%20and%20access/24-Implement%20Conditional%20Access%20Policies%20including%20Multi-Factor%20Authentication.md)

[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)