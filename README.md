# TON Liquid Staking Platform

> A liquid staking platform and DEX backend service for the TON blockchain — stake and unstake TON, track pool data and prepare staking transactions through a clean API.

## What it is

This project documents a **TON blockchain liquid staking service**. It exposes a backend API that lets applications query staking pool data, check user balances, and prepare `stake` / `unstake` transactions for TON smart contracts.

Liquid staking lets token holders earn staking rewards while keeping a liquid, tradable representation of their staked assets — combining the yield of staking with the flexibility of DeFi.

## Key features

- **Liquid staking for TON** — stake TON and receive a liquid staked-asset position.
- **Stake / unstake transaction preparation** — the API builds the transaction payloads that wallets sign and submit to TON smart contracts.
- **Pool data** — query live staking pool statistics.
- **Balance lookups** — fetch staked and available balances for an address.
- **Wallet integration** — works with TON Connect compatible wallets.
- **DEX backend service** — designed as the backend layer for a decentralized exchange and staking front-end.

## How it works

1. A user connects a TON Connect compatible wallet.
2. The front-end requests pool data and the user's balance from the API.
3. The user chooses an amount to stake or unstake.
4. The API prepares the corresponding transaction payload.
5. The wallet signs and submits the transaction to the TON smart contract.

## Documentation

- [Getting started](docs/getting-started.md)
- [Features](docs/features.md)
- [FAQ](docs/faq.md)
- [API reference](API.md)

## Who it is for

- TON holders who want to earn staking rewards while keeping liquidity
- DeFi builders who need a staking backend for a TON exchange or wallet
- Projects integrating TON liquid staking into their product

## По-русски

**Платформа ликвидного стейкинга TON и backend-сервис для DEX.** Сервис предоставляет API: данные пула, балансы пользователей, подготовка транзакций stake/unstake для смарт-контрактов TON. Ликвидный стейкинг позволяет получать доход от стейкинга, сохраняя ликвидную позицию. Подходит держателям TON и DeFi-разработчикам, которым нужен staking-бэкенд для биржи или кошелька. Работает с кошельками, совместимыми с TON Connect.

## FAQ

**What is liquid staking?** It lets you earn TON staking rewards while holding a liquid, tradable representation of your staked position.

**Which blockchain?** TON (The Open Network).

**Which wallets are supported?** Any wallet compatible with TON Connect.

## Related projects

A network of related Telegram bots, Mini Apps and web tools:

- [Telegram Mini App Tap Game — smmtake.ru](https://github.com/DeFiTON/telegram-miniapp-tap-game-smmtake)
- [Telegram Mini App Tap Game — stenbit.ru](https://github.com/DeFiTON/telegram-miniapp-tap-game-stenbit)
- [Telegram Mini App Tap Game — likfool.ru](https://github.com/DeFiTON/telegram-miniapp-tap-game-likfool)
- [Telegram Mini App Tap Game — Terminus](https://github.com/DeFiTON/telegram-miniapp-tap-game-terminus)
- [Telegram Stars CPA Tasks Bot](https://github.com/DeFiTON/telegram-stars-cpa-tasks-bot)
- [Telegram SMM Services Bot + URL Shortener](https://github.com/DeFiTON/telegram-smm-services-bot-urlgo)
- [Telegram Social Media Auto-Posting Bot](https://github.com/DeFiTON/telegram-social-media-autoposting-bot)
- [Telegram ID Checker Bot](https://github.com/DeFiTON/telegram-id-checker-bot)
- [Crypto Trading Chat Access Bot](https://github.com/DeFiTON/crypto-trading-chat-access-bot)
- [Telegram Video Downloader Bot — SaveFastVideoFree](https://github.com/DeFiTON/telegram-video-downloader-bot-savefast)
- [Telegram Video Downloader Bot — SaveAsVideoFree](https://github.com/DeFiTON/telegram-video-downloader-bot-saveas)
- [Telegram Video Downloader Bot — SaveVideoPro](https://github.com/DeFiTON/telegram-video-downloader-bot-savepro)
- [Charity Foundation Website](https://github.com/DeFiTON/charity-foundation-website)
