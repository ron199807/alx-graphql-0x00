# Character Information Queries

This repository contains GraphQL queries to fetch character information from the Rick and Morty API.

## Files

### Single Character Queries
For each character ID (1 through 4):
- `character-id-X.graphql`: GraphQL query to fetch character details
- `character-id-X-output.json`: Expected output for the query

### Paginated Character Queries
For each page (1 through 4):
- `characters-page-X.graphql`: GraphQL query to fetch paginated character list
- `characters-page-X-output.json`: Expected output structure for the query

## Query Details

### Single Character Query
Requests the following fields for a specific character:
- id
- name
- status
- species
- type
- gender

### Paginated Character Query
Requests the following fields for each character in the results:
- id
- name
- status
- image

The paginated queries use the `characters(page: Int)` field to fetch lists of characters by page number.