# Character Information Queries

This repository contains GraphQL queries to fetch character information from the Rick and Morty API.

## Files

For each character ID (1 through 4), there are two files:
- `character-id-X.graphql`: Contains the GraphQL query to fetch character details
- `character-id-X-output.json`: Contains the expected output for the query

## Query Details

Each query requests the following fields for a specific character:
- id
- name
- status
- species
- type
- gender

The queries use the `character(id: ID!)` field to fetch information about a specific character by their ID.