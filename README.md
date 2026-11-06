# 0xdice — Smart Contract Security Portfolio

I'm Victor Chukwu (0xdice), an independent smart contract security researcher since March 2023. I review Solidity and Rust codebases across lending, AMMs, perpetuals, staking, bridges and L2 infrastructure, and prove every finding with a working exploit and Foundry tests.

- [Contact](#contact)
- [About](#about)
- [Track record](#track-record)
- [Notable findings](#notable-findings)
- [Competitive audits](#competitive-audits)
- [Private audits](#private-audits)


## Contact

For private audits or security reviews:

- Email: [chukwuvictor991@gmail.com](mailto:chukwuvictor991@gmail.com)
- Twitter: [@0xdice91](https://x.com/0xdice91)
- Discord: @0xdice91
- Telegram: [@dice91](https://t.me/dice91)

## About

- Competitive audits on Code4rena, Sherlock, Cantina and CodeHawks
- Private audits for Panoptic and six protocols through Secure3
- Audit team lead at Severity Squad
- Currently Smart Contract Engineer at [Chessdict](https://www.chessdict.com)

## Track record

Verified on my [Sherlock profile](https://audits.sherlock.xyz/watson/0xdice91), which tracks Sherlock, Code4rena and CodeHawks results:

| High findings | Medium findings | Payouts | 1st places | Top 10 | Top 25 |
|---|---|---|---|---|---|
| 12 | 10 | 20 | 1 | 5 | 12 |

## Notable findings

| Severity | Finding | Contest |
|---|---|---|
| High | Missing access control in `WERC7575Vault` allows unauthorized withdrawals | SukukFi · Code4rena · #8 |
| High | Order double-linked list breaks because `order.prevOrderId` is not persisted | GTE Spot CLOB and Router · Code4rena · #12 |
| Medium | `FULL_RESTRICTED` users can still stake NUSD due to insufficient checks | Neutrl Protocol · Sherlock · 1st place |

## Competitive audits

Selected contests:

| Contest | Platform | Protocol type | Result | Link |
|---|---|---|---|---|
| Base (with shealtielanz) | Code4rena | Ethereum L2 | ≈ $8,000 | [Contest](https://code4rena.com/audits/2023-05-base) |
| Panoptic | Code4rena | Perpetual options | ≈ $8,100 | [Contest](https://code4rena.com/audits/2024-04-panoptic) |
| Noya (with Severity Squad) | Code4rena | Omnichain liquidity, ZKML | ≈ $2,000 | [Contest](https://code4rena.com/audits/2024-04-noya) |
| Ajna Protocol | Code4rena | Oracle-free lending | ≈ $1,000 | [Contest](https://code4rena.com/audits/2023-05-ajna-protocol) |
| UniStaker Infrastructure | Code4rena | Uniswap governance staking | ≈ $1,000 | [Contest](https://code4rena.com/audits/2024-02-unistaker-infrastructure) |
| Neutrl Protocol | Sherlock | Synthetic dollar | 🥇 1st | [Contest](https://audits.sherlock.xyz/contests/1065) |
| Avon | Cantina | Lending | ≈ $1,000 | [Contest](https://cantina.xyz/code/708eecf5-a6a0-46c1-a949-277f7408decc/overview) |
| SukukFi | Code4rena | Tokenized vaults | #8 | |
| GTE Spot CLOB and Router | Code4rena | Order-book DEX | #12 | |
| Brahma | Code4rena | Custody and DeFi execution | #14 | [Contest](https://code4rena.com/audits/2023-10-brahma) |
| Canto Liquidity Mining | Code4rena | Liquidity mining | #15 | [Contest](https://code4rena.com/audits/2023-10-canto-liquidity-mining-protocol) |
| Munchables | Code4rena | GameFi | #15 | |
| RealWagmi | Sherlock | DEX on zkSync | #20 | [Contest](https://audits.sherlock.xyz/contests/88?filter=results) |
| Venus Prime | Code4rena | Lending rewards | #39 | |
| Chainlink Staking v0.2 | Code4rena | Oracle staking | | |
| Dodo V3 | Sherlock | Leveraged market making | | [Contest](https://audits.sherlock.xyz/contests/89) |
| DODO Cross-Chain DEX | Sherlock | Cross-chain DEX | | [Contest](https://audits.sherlock.xyz/contests/991) |
| Flayer | Sherlock | NFT liquidity, Uniswap V4 hooks | | [Contest](https://audits.sherlock.xyz/contests/468) |
| Liquidity Management (Gamma) | CodeHawks | Perpetual vaults on GMX | | [Contest](https://codehawks.cyfrin.io/c/2025-02-gamma/results?lt=contest&page=1&sc=reward&sj=reward&t=leaderboard) |
| Zaros Part 1 | CodeHawks | Perpetuals DEX | | [Contest](https://codehawks.cyfrin.io/c/2024-07-zaros) |
| eBTC Stability Module (Badger) | Cantina | Stablecoin swaps | | [Contest](https://cantina.xyz/code/f57ffb47-0ded-4f04-bcec-ecd7d47fad58/overview/leaderboard) |
| Alchemix v3 | Cantina | Self-repaying loans | | [Contest](https://cantina.xyz/code/e68909e6-3491-4a94-a707-ecf0c89cf72a/overview) |

## Private audits

| Protocol | Scope | Language | Report |
|---|---|---|---|
| Panoptic (via Code4rena) | Two-week review of new logic plus mitigation review | Solidity | [Report](https://code4rena.com/reports/2024-09-panoptic) |
| Secure3 (6 protocols) | Lending, staking, AMM and cross-chain reviews | Solidity | Under NDA |

