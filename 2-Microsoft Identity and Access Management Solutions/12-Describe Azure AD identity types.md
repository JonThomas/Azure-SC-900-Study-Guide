# Describe Azure AD identity types (users, devices, groups, service principals/applications)

[Describe Azure AD identity types](https://docs.microsoft.com/en-us/learn/modules/explore-basic-services-identity-types/4-describe-identity-types)

* Users - Pretty obvious.
    * Guest users from an other organization can be allowed access using Azure B2B - a feature within External Identities: 
* Groups - Users with similar access needs can be added to a group. Access can then be configured on the group
* Service principals ~ identity for an application. See [Service Principals @ AZ-500](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/1-Manage%20identity%20and%20access/11-Configure%20security%20for%20service%20principals.md)
* Managed Identity - Eliminates the need for developers to manage credentials
    * You can use managed identities to authenticate to any resource that supports Azure AD authentication, including your own applications.
    * Managed identities can be used without any additional cost.
* Devices 
    * Azure AD registered device: Typically a personal device, signed in using personal MS account, or other account. Ex: Private iPhone.
    * Azure AD joined device: A Windows 10 device owned by the organization, and signed in using the organization account.
    * Hybrid Azure AD joined device: Any Windows device.

[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)