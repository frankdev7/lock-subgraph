# Lock Subgraph

## Subgraph Endpoint

[https://api.studio.thegraph.com/query/48805/lock-subgraph/version/latest](https://api.studio.thegraph.com/query/48805/lock-subgraph/version/latest)

## Lock Smart Contract Repository

[https://github.com/frankdev7/Lock](https://github.com/frankdev7/Lock)

## Sample Query

Here's an example GraphQL query which fetches the first 5 withdrawals:

```graphql
{
  withdrawals(first: 5) {
    id
    amount
    when
    blockNumber
  }
}