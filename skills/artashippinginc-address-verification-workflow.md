---
name: artashippinginc-address-verification-workflow
description: Create an address verification, retrieve its details, and list all address verifications.
api: openapi/arta-openapi.json
operations:
- addressVerifications/create
- addressVerifications/get
- addressVerifications/list
generated: '2026-09-26'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/arta-openapi.json ; every operationId checked against the contract
---

# artashippinginc-address-verification-workflow

Create an address verification, retrieve its details, and list all address verifications.

## Steps

1. 1. Use `addressVerifications/create` – request body fields are not specified in the documentation.
2. 2. Use `addressVerifications/get` – provide the path parameter `address_verification_id`.
3. 3. Use `addressVerifications/list` – no query parameters or headers are documented.

## Rules

- No authentication header is documented.
- No idempotency key requirement is documented.
- Pagination details are not provided for the list operation.
- Error response formats are not described.
