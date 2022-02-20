# Describe ways Azure encrypts data

[Describe ways Azure encrypts data](https://docs.microsoft.com/en-us/learn/modules/describe-basic-security-capabilities-azure/7-describe-ways-azure-encrypts-data)

## Encryption
* Azure Storage Service Encryption
    * Automatically encrypts data at rest, before persting it to disk, in Azure Blob Storage, Azure Files and Azure Queue Storage
* Azure Disk Encryption
    * Encrypts Windows disks with BitLocker
    * Encrypts Linux IaaS virtual machine disks with dm-crypt
* Transparent data encryption (TDE)
    * Real-time encryption (and decryption) of Azure SQL and Azure Warehouse database, including backups and transaction log files at rest

## Azure Key Vault
* Store application secrets
    * Tokens
    * Passwords
    * Certificates
    * Encryption keys
* Secure access
* Permission control
* Access logging capabilities
* Certificate management
* Backed by Hardware Security Modules (HSMs)
    * Software or hardware

[Return to Microsoft Security Solutions](README.md)

[Return to Table of Contents](../README.md)