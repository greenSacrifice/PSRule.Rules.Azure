---
severity: Important
pillar: Security
category: Identity and access management
resource: Subscription
online version: https://github.com/Azure/PSRule.Rules.Azure/blob/main/docs/en/rules/Azure.RBAC.UseGroups.md
ms-content-id: 818cc242-5912-44b6-b3dc-461822079522
---

# Use groups

## SYNOPSIS

Use groups for assigning permissions instead of individual user accounts.

## DESCRIPTION

Granting access with individual user accounts can bypass existing on-premises identity management tools and processes.

## RECOMMENDATION

Consider using groups for assigning permissions instead of individual user accounts.

## LINKS

- [Avoid granular and custom permissions](https://docs.microsoft.com/azure/architecture/framework/security/design-admins#avoid-granular-and-custom-permissions)
- [What is Azure role-based access control (Azure RBAC)?](https://docs.microsoft.com/azure/role-based-access-control/overview)
