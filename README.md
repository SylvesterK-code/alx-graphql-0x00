# Episode Queries


mkdir episode
ni README.md
ni episode-id-1.graphql
ni episode-id-1-output.json
ni episode-id-2.graphql
ni episode-id-2-output.json
ni episode-id-3.graphql
ni episode-id-3-output.json
ni episode-id-4.graphql
ni episode-id-4-output.json


## Query to get episode by ID
This query fetches details of a specific episode using the `episode(id: ID!)` field.

### Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}











# Episode Queries

This directory contains GraphQL queries and outputs for retrieving specific episodes by ID from the Rick and Morty GraphQL API.

## Queries

- `episode-id-1.graphql` → Fetch episode with ID 1
- `episode-id-2.graphql` → Fetch episode with ID 2
- `episode-id-3.graphql` → Fetch episode with ID 3
- `episode-id-4.graphql` → Fetch episode with ID 4

## Outputs

Each query result is saved in:
- `episode-id-1-output.json`
- `episode-id-2-output.json`
- `episode-id-3-output.json`
- `episode-id-4-output.json`




git add .
git commit -m "2. Write a Query to Get a Specific Episode by ID 1-4"
git push origin main