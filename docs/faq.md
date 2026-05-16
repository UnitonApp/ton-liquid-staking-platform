# FAQ

**What is liquid staking?**
Liquid staking lets you earn TON staking rewards while holding a liquid, tradable representation of your staked position — so your capital is not fully locked.

**Which blockchain does it use?**
TON (The Open Network).

**Which wallets are supported?**
Any wallet compatible with the TON Connect standard.

**Does the service hold my funds?**
No. The API only prepares transaction payloads. Signing and submission happen in your own wallet, and staking logic is enforced by on-chain smart contracts.

**Is there an API?**
Yes. The service exposes an HTTP API with interactive documentation at `/docs`. See the [API reference](../API.md).

**How do I unstake?**
Choose an amount to unstake in the front-end; the API prepares an `unstake` transaction that your wallet signs and submits.
