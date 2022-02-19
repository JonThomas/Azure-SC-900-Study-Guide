# Describe password protection and management capabilities

[Describe password protection and management capabilities](https://docs.microsoft.com/en-us/learn/modules/explore-authentication-capabilities/6-describe-password-protection-management)

Azure AD Password Protection reduces the risk that users set weak passwords.

* Blocks known weak passwords, using global banned password lists
    * Global list is updated based on real-world telemetry data from Azure AD
* Can block weak terms spesific to your organization, using a "custom" password list.
* All variations of a banned password are also banned, both in global and custom banned lists:
    * All variations on text case and letters to numbers are applied, so if "password" is banned, then "Password" and "passw0rd" are also banned.
* Extra benefit: Protection against password spray (since password spray tries same weak password against all accounts, and all weak passwords are already in Global list)
* Global and custom password lists can be received by on-site AD Domain controllers, so that password protection can be enforced wherever the user changes password.

[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)