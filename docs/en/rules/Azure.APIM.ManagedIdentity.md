---
severity: Important
pillar: Security
category: Identity and access management
resource: API Management
online version: https://github.com/Azure/PSRule.Rules.Azure/blob/main/docs/en/rules/Azure.APIM.ManagedIdentity.md
---

# API Management uses a managed identity

## SYNOPSIS

Configure managed identities to access Azure resources.

## DESCRIPTION

API Management must authenticate to access Azure resources such as Key Vault.
Use Key Vault to store certificates and secrets used within API Management.

## RECOMMENDATION

Consider configuring a managed identity for each API Management instance.
Also consider using managed identities to authenticate to related Azure services.

## LINKS

- [Use identity-based authentication](https://docs.microsoft.com/azure/architecture/framework/security/design-identity-authentication#use-identity-based-authentication)
- [Use managed identities in Azure API Management](https://docs.microsoft.com/azure/api-management/api-management-howto-use-managed-service-identity)
- [Authenticate with managed identity](https://docs.microsoft.com/azure/api-management/api-management-authentication-policies#ManagedIdentity)
- [Azure template reference](https://docs.microsoft.com/azure/templates/microsoft.apimanagement/2019-12-01/service#ApiManagementServiceIdentity)
