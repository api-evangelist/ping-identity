---
name: ping-identity-manage-davinci-admin-variables
description: Create, retrieve, update, and delete a DaVinci Admin variable in a specific environment.
api: openapi/ping-identity-davinci-admin-variables-api-openapi.yml
operations:
- createVariable
- getVariableById
- replaceVariableById
- deleteVariableById
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/ping-identity-davinci-admin-variables-api-openapi.yml ; every operationId checked against the contract
---

# ping-identity-manage-davinci-admin-variables

Create, retrieve, update, and delete a DaVinci Admin variable in a specific environment.

## Steps

1. 1. Use `createVariable` with the request body fields `name`, `value`, and optional `description` to create a new variable.
2. 2. Use `getVariableById` with the path parameters `environmentID` and `variableID` to retrieve the created variable.
3. 3. Use `replaceVariableById` with the path parameters `environmentID` and `variableID` and request body fields `name`, `value`, and optional `description` to update the variable.
4. 4. Use `deleteVariableById` with the path parameters `environmentID` and `variableID` to delete the variable.

## Rules

- Include an `Authorization: Bearer <token>` header (bearerAuth) on every request.
- OAuth2 token must be obtained via the provider's OAuth2 flow (oauth2).
- No rate‑limit information is provided; assume no specific limit.
