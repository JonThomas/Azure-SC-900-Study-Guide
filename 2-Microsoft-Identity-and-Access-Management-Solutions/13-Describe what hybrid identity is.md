# Describe what hybrid identity is

[Describe what hybrid identity is](https://docs.microsoft.com/en-us/learn/modules/explore-basic-services-identity-types/6-describe-concept-of-hybrid-identities)

* Hybrid identity: Identities (users) are created and managed in on-prem AD installations (or other identity providers), and then synchronized to Azure AD.
    * Sync is managed using Azure AD Connect
    * Managed auth: Users authenticate with AD
    * Federated auth: Users Azure AD requests auth by other IdP
vs
* Cloud only idenity: Identities are created and managed in Azure
* Users can access on-prem resources, no matter which identiy model is used.

Read more about the three [Authentication methods in the AZ-500 study guide](https://docs.microsoft.com/en-us/learn/modules/explore-basic-services-identity-types/6-describe-concept-of-hybrid-identities)
    * Password hash sync (a hash of the password is kept in the cloud)
    * Pass-through auth (auth is redirected to on-prem AD)
    * Federated auth


[Return to Microsoft Identity and Access Management Solutions](README.md)

[Return to Table of Contents](../README.md)