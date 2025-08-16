# alx-graphql-0x00

## Character Information Retrieval (by ID)

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




## Paginated List of Characters

This directory contains GraphQL queries to retrieve a paginated list of characters using the `characters(page: Int)` field. Each query fetches the following fields for characters on a specific page:
- `id`
- `name`
- `status`
- `image`

### Files
- `characters-page-1.graphql`: Query for characters on page 1.
- `characters-page-1-output.json`: Expected output for page 1 query.
- `characters-page-2.graphql`: Query for characters on page 2.
- `characters-page-2-output.json`: Expected output for page 2 query.
- `characters-page-3.graphql`: Query for characters on page 3.
- `characters-page-3-output.json`: Expected output for page 3 query.
- `characters-page-4.graphql`: Query for characters on page 4.
- `characters-page-4-output.json`: Expected output for page 4 query.

