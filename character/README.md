# alx-graphql-0x00

## Character Directory

This directory contains GraphQL queries to retrieve character information using the `character(id: ID!)` field. Each query fetches the following fields for a specific character:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

### Files
- `character-id-1.graphql`: Query for character with ID 1.
- `character-id-1-output.json`: Expected output for character ID 1 query.
- `character-id-2.graphql`: Query for character with ID 2.
- `character-id-2-output.json`: Expected output for character ID 2 query.
- `character-id-3.graphql`: Query for character with ID 3.
- `character-id-3-output.json`: Expected output for character ID 3 query.
- `character-id-4.graphql`: Query for character with ID 4.
- `character-id-4-output.json`: Expected output for character ID 4 query.

### Usage
These queries are designed to work with a GraphQL API that supports the `character(id: ID!)` query, such as the Rick and Morty API. 