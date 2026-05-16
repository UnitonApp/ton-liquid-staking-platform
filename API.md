# API Reference

The TON Liquid Staking Platform exposes an HTTP API for staking operations. Interactive API documentation (Swagger UI) is served at `/docs` when the service is running.

## Capabilities

| Capability | Description |
|---|---|
| Get staking pool data | Returns live statistics for the staking pool |
| Get balance | Returns staked and available balance for a TON address |
| Prepare stake | Builds a `stake` transaction payload for a given amount |
| Prepare unstake | Builds an `unstake` transaction payload for a given amount |

## Flow

1. The client requests **pool data** to display current pool statistics.
2. The client requests the connected wallet's **balance**.
3. When the user chooses to stake, the client calls **prepare stake** with the amount.
4. The API returns a transaction payload.
5. The user's TON Connect wallet signs and submits the transaction to the on-chain smart contract.
6. Unstaking follows the same pattern via **prepare unstake**.

## Notes

- The API only prepares transactions; signing and submission always happen in the user's wallet.
- All staking logic is enforced by TON smart contracts on-chain.
- The root path `/` serves an HTML help page, and `/docs` serves interactive Swagger documentation.
