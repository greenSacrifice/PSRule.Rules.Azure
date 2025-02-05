---
severity: Awareness
pillar: Operational Excellence
category: Tagging and resource naming
resource: Cognitive Search
online version: https://github.com/Azure/PSRule.Rules.Azure/blob/main/docs/en/rules/Azure.Search.Name.md
---

# Use valid Cognitive Search service names

## SYNOPSIS

Azure Cognitive Search service names should meet naming requirements.

## DESCRIPTION

When naming Azure resources, resource names must meet service requirements.
The requirements for Cognitive Search service names are:

- Between 2 and 60 characters long.
- Lowercase letters, numbers, and hyphens.
- The first two and last one character must be a letter or a number.
- Cognitive Search service names must be globally unique.

## RECOMMENDATION

Consider using names that meet Azure Cognitive Search service naming requirements.
Additionally consider naming resources with a standard naming convention.

## NOTES

This rule does not check if Azure Cognitive Search service names are unique.

## LINKS

- [REST API reference](https://docs.microsoft.com/rest/api/searchmanagement/2021-04-01-preview/services/create-or-update)
- [Define your naming convention](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)
- [Recommended abbreviations for Azure resource types](https://docs.microsoft.com/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)
