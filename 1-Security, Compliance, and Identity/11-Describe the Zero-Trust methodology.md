# Describe the Zero-Trust methodology

[Zero-Trust methodology](https://docs.microsoft.com/en-us/learn/modules/describe-security-concepts-methodologies/2-describe-zero-trust-methodology)

The Zero Trust model operates on the principle of “trust no one, verify everything.”

Three underlying principles: 
* Verify explicitly: Always verify credentials using the user identity, location, device, service or workload, data classification and anomalities
* Least privileged access: Limit user access with just-in-time and just-enough access (JIT/JEA), risk-based adaptive policies, and data protection to protect both data and productivity.
    * Just-in-time access to resources in Azure is set up most commonly using [Conditional Access Policies](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/1-Manage%20identity%20and%20access/24-Implement%20Conditional%20Access%20Policies%20including%20Multi-Factor%20Authentication.md) but also [Privileged Identity Management (PIM)](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/1-Manage%20identity%20and%20access/21-Monitor%20privileged%20access%20for%20Azure%20AD%20Privileged%20Identity%20Management%20(PIM).md)
    * Just-in-time access to VMs in Azure can be set up using [Azure Security Center](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/3-Manage%20security%20operations/22-Configure%20Just%20in%20Time%20VM%20access%20by%20using%20Azure%20Security%20Center.md)
* Assume breach: Segment access by network, user, devices, and application. Use encryption to protect data, and use analytics to get visibility, detect threats, and improve your security.
    * Use [VNets to segment networks](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/2-Implement%20platform%20protection/10-Secure%20the%20connectivity%20of%20virtual%20networks%20(VPN%20authentication,%20Express%20Route%20encryption).md) in Azure
    * Use [Azure AD](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/1-Manage%20identity%20and%20access/README.md) to manage user access
    * [Storage data is always encrypted](https://github.com/JonThomas/Azure-AZ-500-Study-Guide/blob/master/4-Secure%20data%20and%20applications/16-Implement%20Storage%20Service%20Encryption.md) in Azure. Database encryption can also be set up.


[Return to Security, Compliance and Identity](README.md)

[Return to Table of Contents](../README.md)