# Describe self-service password reset

[Describe self-service password reset](https://docs.microsoft.com/en-us/learn/modules/explore-authentication-capabilities/5-describe-self-service-password-reset)

* Many benefits of setting up Self Service Password Reset (SSPR), for example less manual work for user admins.
* Administrators are enabled for SSPR by default, and require two auth methods to change password (Security questions are not allowed)
* Email notification can be set up, so that users are notified when an SSPR event happens.

## Password writeback

[Configure password writeback](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-sspr-writeback)

* Used to write passwords changed in Azure AD back to onsite AD.
* Only relevant in hybrid scenarious (obviously) and when Self Service Password Reset (SSPR) has been configured i Azure AD (also obvious)

[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)