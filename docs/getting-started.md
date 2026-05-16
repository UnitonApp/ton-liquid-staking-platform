# Getting Started

The TON Liquid Staking Platform is a backend service for staking TON.

## For users

1. Open the staking front-end and connect a TON Connect compatible wallet.
2. Review the current pool statistics and your balance.
3. Enter an amount of TON to stake.
4. Confirm the transaction in your wallet.
5. To exit, choose an amount to unstake and confirm again.

Your staked TON earns rewards while you keep a liquid position you can manage.

## For developers

The platform provides an HTTP API that:

- Returns staking pool data.
- Returns staked and available balances for an address.
- Prepares `stake` and `unstake` transaction payloads.

Interactive API documentation is available at `/docs` (Swagger UI) once the service is running. See [API.md](../API.md) for the reference.
