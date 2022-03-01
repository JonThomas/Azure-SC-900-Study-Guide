# Describe Multi-factor Authentication

[Describe Multi-factor Authentication](https://docs.microsoft.com/en-us/learn/modules/explore-authentication-capabilities/2-describe-multi-factor-authentication)

Multi factor authentication: Using more than one means for authenticating, for example finger print or a trusted device in addition to password:
* Something you know: Password or PIN

**AND**

* Something you have: Phone or hardware key **OR**
* Something you are: Fingerprint or face scan

Multi factor authentication can be required in Azure AD by an administrator, or set up bu user in their MyAccount.

MfA in Azure AD:
* Microsoft Authenticator app
* SMS
* Voice call
* OATH Hardware token

Security Defaults (recommended by Microsoft):
* [Enforce Azure AD MfA registration for all users](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/concept-fundamentals-security-defaults#unified-multi-factor-authentication-registration): Once enabled, users have 14 days until they are forced to register for MfA. 
* Force administrators to use MfA
* [Require all users to complete MfA when needed](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/concept-fundamentals-security-defaults#protecting-all-users) (based on their actions, location, device, role and task)
* Blocking legacy authentication protocols (Office 2010 client, IMAP, POP3, SMTP, Exchange Active Sync basic auth)
    * When security defaults are enabled on the Azure tenant, these auth requests are blocked.

[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)