---
name: artashippinginc-manage-uploads
description: Manage upload resources by listing, creating, retrieving, and deleting uploads.
api: openapi/arta-openapi.json
operations:
- uploads/list
- uploads/create
- uploads-get
- uploads/delete
generated: '2026-09-26'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/arta-openapi.json ; every operationId checked against the contract
---

# artashippinginc-manage-uploads

Manage upload resources by listing, creating, retrieving, and deleting uploads.

## Steps

1. 1. Use `uploads/list` to retrieve a list of uploads.
2. 2. Use `uploads/create` to create a new upload.
3. 3. Use `uploads-get` to retrieve details of a specific upload by `upload_id`.
4. 4. Use `uploads/delete` to delete a specific upload by `upload_id`.

## Rules

- (none stated)
