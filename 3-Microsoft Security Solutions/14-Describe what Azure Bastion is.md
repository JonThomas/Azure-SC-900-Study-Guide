# Describe what Azure Bastion is

[Describe what Azure Bastion is](https://docs.microsoft.com/en-us/learn/modules/describe-basic-security-capabilities-azure/5-describe-what-azure-bastion)

* Azure Bastion is used instead of RDP'ing or SSH'ing directly into an Azure VM
* VMs are accessed and managed directly from within the Azure Portal, using TLS
   * RDP packets never leave Azure
   * VM is always accessed using a private IP, never any public IPs.
* Microsoft recommends Azure Bastion whenever you have a VM that you need to log in to.
* Azure Bastion is a fully managed service in your virtual network in Azure
   * Your VM doesn't have to expose any public IPs to the internet
* Once Azure Bastion is deployed, any VM in the VNet can be accessed
    * Bastion provides connectivity to all VMs in the vNet and peered vNets
* Internally Azure Bastion is a VM Scale Set, that can resize itself, and runs a set of applications and daemons


[Return to Microsoft Security Solutions](README.md)

[Return to Table of Contents](../README.md)