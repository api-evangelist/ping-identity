---
name: ping-identity-create-and-retrieve-connector-instance
description: Create a new connector instance and then retrieve its details.
api: openapi/ping-identity-davinci-admin-connector-instances-api-openapi.yml
operations:
- createConnectorInstance
- getConnectorInstanceById
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/ping-identity-davinci-admin-connector-instances-api-openapi.yml ; every operationId checked against the contract
---

# ping-identity-create-and-retrieve-connector-instance

Create a new connector instance and then retrieve its details.

## Steps

1. 1. Use `createConnectorInstance` with required body fields as defined in the contract.
2. 2. Use `getConnectorInstanceById` with the `environmentID` path parameter and the `connectorInstanceID` returned from the create step.

## Rules

- Include a Bearer token in the `Authorization` header as required by the `bearerAuth` scheme.
- No rate limit is defined; on exhaustion the API returns no specific HTTP status.
