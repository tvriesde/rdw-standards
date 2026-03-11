---
applyTo: "**/*.bicep"
---
# Bicep Standards
- Use camelCase for variable and parameter names.
- Use PascalCase for resource names.
- Include comments to explain the purpose of complex resources and modules.
- Avoid hardcoding values; use parameters and variables instead.
- Organize resources logically, grouping related resources together.
- Use resource naming conventions that reflect the purpose and environment (e.g., dev, prod).
- Use the following prefix for resource names: [project]-[environment]-[resourceType]-[uniqueIdentifier]. For example: myapp-dev-storageaccount-001.
