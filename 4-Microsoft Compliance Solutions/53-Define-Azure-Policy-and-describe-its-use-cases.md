# Define Azure Policy and describe its use cases

[Define Azure Policy and describe its use cases](https://docs.microsoft.com/en-us/learn/modules/describe-resource-governance-capabilities-azure/4-describe-azure-policy)

Common use cases for Azure Policy include:
* Implementing governance for resource consistency
* Regulatory compliance
* Security
* Cost
* Management.

Azure Policy evaluates all resources in Azure and Arc enabled resources (specific resource types hosted outside of Azure).

## Policy Definitions
* Describes the business rules of a policy
* JSON

## Policy Initiative
* A group of policy definitions

## Assign policy to resources
* A policy definition or intiative can be assigned to any scope of resources that are supported:
    * Management group
    * Subscription
    * Resource group
    * Resource

## Evaluate outcome

The following events or times will trigger an evaluation:
* A resource has been created, deleted, or updated in scope with a policy assignment.
* A policy or an initiative is newly assigned to a scope.
* A policy or an initiative that's been assigned to a scope is updated.
* The standard compliance evaluation cycle (happens once every 24 hours).

Organizations will vary in how they respond to non-compliant resources. Here's some examples:
* Deny a change to a resource.
* Log changes to a resource.
* Alter a resource before or after a change.
* Deploy related compliant resources.

With Azure Policy, responses like these are made possible by using effects, which are specified in policy definitions.

[Return to Microsoft Compliance Solutions](README.md)

[Return to Table of Contents](../README.md)