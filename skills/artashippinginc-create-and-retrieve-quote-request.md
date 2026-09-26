---
name: artashippinginc-create-and-retrieve-quote-request
description: Create a new quote request and then retrieve its details.
api: openapi/arta-openapi.json
operations:
- requests/create
- requests/get
generated: '2026-09-26'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/arta-openapi.json ; every operationId checked against the contract
---

# artashippinginc-create-and-retrieve-quote-request

Create a new quote request and then retrieve its details.

## Steps

1. 1. Use `requests/create` with the request body fields defined in the contract to create a quote request.
2. 2. Use `requests/get` with the path parameter `request_id` returned from the create call to retrieve the quote request details.

## Rules

- Include the required authentication header as specified by the API (e.g., `Authorization: Bearer <token>`).
- Handle standard HTTP error responses such as 4xx for client errors and 5xx for server errors.
