
# Episode Information Queries

This repository contains GraphQL queries to fetch episode information from the Rick and Morty API.

## Files

For each episode ID (1 through 4), there are two files:
- `episode-id-X.graphql`: Contains the GraphQL query to fetch episode details
- `episode-id-X-output.json`: Contains the expected output for the query

## Query Details

Each query requests the following fields for a specific episode:
- id
- name
- air_date
- episode (season and episode number)

The queries use the `episode(id: ID!)` field to fetch information about a specific episode by its ID.