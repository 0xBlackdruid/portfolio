# Blackdruid

Security researcher across smart contract audits, web application security, and live bug bounty programs. Focused on the structural soundness of protocols: DeFi logic, accounting assumptions, cross-contract interactions, and the EVM details that turn small mistakes into critical vulnerabilities. Currently specializing in Zero Knowledge Proof protocols. Background spanning Web3 research, Web2 bug hunting, vulnerability assessment, IT audit, and risk advisory, treating security as both a code level and a business risk problem.

---

## Smart Contract Audit Competitions

| Protocol | Class | Severity | Report |
|:--|:--|:--:|:--:|
| [Alchemix V3](https://alchemix.fi/) | Self-repaying loans protocol | Critical | [report](https://reports.immunefi.com/alchemix-v3) |
| [Fluid DEX v2](https://blog.instadapp.io/fluid-dex-v2/) | Instadapp decentralized exchange | Medium | [#12](https://audits.sherlock.xyz/contests/1225/voting/1278) |
| [Chainlink Payment Abstraction V2](https://blog.chain.link/payment-abstraction-svr-fee-conversion/) | Fee-conversion system (→ LINK) | Low | [S-1520](https://code4rena.com/audits/2026-03-chainlink-payment-abstraction-v2/submissions/S-1520) |
| [Panoptic](https://panoptic.xyz/) | Perpetual options on Uniswap | Medium | — |

## Web2 Bug Bounty

| Target | Class | Severity |
|:--|:--|:--:|
| T-Mobile | US wireless telecom carrier | 2× High |
| Swiss Post | National postal service of Switzerland | High · Medium |
| Harman Audio | Samsung audio / connected-car division | High |

---

## Focus

- **Languages.** Solidity, EVM/Yul, Rust. Cross-ecosystem work on DeFi and distributed-ledger infrastructure.
- **Protocol classes.** Lending and money markets, AMMs and decentralized exchanges, options protocols, oracle and fee-conversion systems, cross-chain infrastructure. Currently going deep on Zero Knowledge Proof protocols.
- **Where I tend to find bugs.** Raw-vs-effective accounting mismatches, stale state in conditional writes, share and liquidity mechanics, oracle integrity, role-boundary violations, and accounting-invariant breaks under boundary conditions.

## How I Work

- **Adversarial-first.** Every state change is a hypothesis until I've traced who can reach it and what it costs to push past intended bounds.
- **Boundary-obsessed.** Zero-state, max-state, first-depositor, last-withdrawer, and dust-amount paths get more attention than the happy path.
- **Mechanical proof, not vibes.** Findings ship with PoCs or concrete numerical traces. If I can't make it break in a test, I don't claim it does.

---

## Profiles

[![Sherlock](https://img.shields.io/badge/Sherlock-Blackdruid-1D5BFF?style=for-the-badge)](https://audits.sherlock.xyz/watson/Blackdruid)
[![Code4rena](https://img.shields.io/badge/Code4rena-Blackdruid-9146FF?style=for-the-badge)](https://code4rena.com/@Blackdruid)
[![Immunefi](https://img.shields.io/badge/Immunefi-blackdruiid-FF3D3D?style=for-the-badge)](https://immunefi.com/profile/blackdruiid/)
[![X](https://img.shields.io/badge/X-@0xblackdruid-000000?style=for-the-badge)](https://x.com/0xblackdruid)

- **Telegram:** Blackdruiid
- **Discord:** 0xblackdruid

## Currently

Open to audit collaborations and private engagements. Especially keen on protocols pushing complex accounting, novel AMM curves, cross-chain messaging primitives, or Zero Knowledge systems.

DMs open on X — [@0xblackdruid](https://x.com/0xblackdruid).
