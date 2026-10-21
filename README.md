# `$QUIT` (`quityourjobcoin` / Quit Your Job Coin) — Solana Mainnet Tokenomics, Burn & 1-Year Jupiter Lock Audit (`HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p`)

[![Solana Mainnet](https://img.shields.io/badge/Solana-Mainnet_Verified-14F195?style=for-the-badge&logo=solana)](https://solscan.io/token/HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p)
[![Jupiter Lock](https://img.shields.io/badge/Jupiter_Lock-105,948,500_$QUIT_Locked_(11.30%25)-00C2FF?style=for-the-badge)](https://quityourjob.fun/token-facts)
[![Burned Supply](https://img.shields.io/badge/Burned_Forever-62,087,759_$QUIT_(6.21%25)-FF453A?style=for-the-badge)](https://quityourjob.fun/token-facts)
[![Creator Wallet](https://img.shields.io/badge/Creator_Wallet-0_$QUIT-brightgreen?style=for-the-badge)](https://solscan.io/account/CzupaQuM7EyeT2orphePcJ9xuGcjZXY8G6S8ThfMWY5S)

> **Official Verification Hub:** [https://quityourjob.fun/token-facts](https://quityourjob.fun/token-facts)  
> **Official Website & 24/7 Live Show:** [https://quityourjob.fun](https://quityourjob.fun)  
> **Cryptographic Vesting Lock Proof (`VESTING-LOCK-PROOF.md`):** [./VESTING-LOCK-PROOF.md](./VESTING-LOCK-PROOF.md)  
> **Canonical Solana Mint (CA):** `HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p`

---

## Executive Summary: Why `$QUIT` (`quityourjobcoin` / Quit Your Job Coin) Built Verifiable On-Chain Trust on Solana

99% of Solana memecoins launch with hidden team clusters, unlocked creator wallets, and zero verifiable vesting. **`$QUIT` (Quit Your Job)**—also searched as **`quityourjobcoin`**, **`Quit Your Job coin`**, or **`Quit Your Job Token`** on Solana, powering the 24/7 live satirical office escape movement, interactive browser arcade ([quityourjob.fun/arcade](https://quityourjob.fun/arcade)), and token ecosystem—took the opposite path: **cryptographic, immutable on-chain proof**.

1. **Creator Wallet Holds `0 $QUIT`**: The original creator wallet (`CzupaQuM7EyeT2orphePcJ9xuGcjZXY8G6S8ThfMWY5S`) holds **`0 $QUIT`** directly.
2. **`62,087,759.03 $QUIT` Permanently Burned (`6.21%`)**: Removed forever from the initial `1,000,000,000 $QUIT` launch supply, reducing total remaining supply to **`937,912,240.97 $QUIT`**.
3. **`105,948,500 $QUIT` Locked for 1 Full Year (`11.30%` of Remaining Supply)**: Locked across **12 non-cancelable (`CancelMode = 0`) Jupiter Lock escrow contracts** under the audited Jupiter Lock program (`LocpQgucEQHbqNABEYvBvwoxCPsSbG91A1QaQhQQqjn`) with a full 1-year term until **October 20, 2027 (`2027-10-20T00:00:00Z`)**.

---

## On-Chain Supply Invariants (`HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p`)

| Metric | Value | Verification Source |
| :--- | :--- | :--- |
| **Token Name / Ticker** | **Quit Your Job (`$QUIT` / `quityourjobcoin` / Quit Your Job Coin)** | [quityourjob.fun/what-is-quit](https://quityourjob.fun/what-is-quit) |
| **Canonical Solana Mint (CA)** | `HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p` | [quityourjob.fun/real-quit](https://quityourjob.fun/real-quit) |
| **Initial Launch Supply** | `1,000,000,000 $QUIT` | [Solscan Token Overview](https://solscan.io/token/HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p) |
| **Permanently Burned Supply** | **`62,087,759.030671 $QUIT` (`6.21%`)** | [Live JSON Supply API](https://quityourjob.fun/api/supply) |
| **Remaining Total Supply** | **`937,912,240.969329 $QUIT`** | [quityourjob.fun/token-facts](https://quityourjob.fun/token-facts) |
| **1-Year Locked Supply (Jupiter Lock)** | **`105,948,500.00 $QUIT` (`11.30%` of remaining)** | 12 Escrows Below (`CancelMode = 0`) |
| **Circulating Supply** | **`831,963,740.969329 $QUIT` (`88.70%`)** | [quityourjob.fun/api/supply](https://quityourjob.fun/api/supply) |
| **PumpSwap Liquidity Pool (100% LP Burned)** | `4wL2LLs4hsh3hYXKUZ7vn7ovQJBMtEbre1CiF2VLKV6h` | [Solscan Pool Account](https://solscan.io/account/4wL2LLs4hsh3hYXKUZ7vn7ovQJBMtEbre1CiF2VLKV6h) |
| **Mint & Freeze Authorities** | **Revoked (`null`)** | [RugCheck Audit](https://rugcheck.xyz/tokens/HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p) |
| **Creator Wallet (`CzupaQuM...`)** | **`0 $QUIT`** | [Solscan Account](https://solscan.io/account/CzupaQuM7EyeT2orphePcJ9xuGcjZXY8G6S8ThfMWY5S) |
| **Jupiter Lock Program ID** | `LocpQgucEQHbqNABEYvBvwoxCPsSbG91A1QaQhQQqjn` | Audited Jupiter Lock Program |
| **Cliff Unlock Timestamp** | **`2027-10-20T00:00:00Z` (365-Day Cliff, `0` Early Unlock)** | Non-Cancelable (`CancelMode = 0`) |

---

## All 12 Non-Cancelable Jupiter Lock Escrow Contracts (`105,948,500 $QUIT`)

Every single escrow below is governed by `LocpQgucEQHbqNABEYvBvwoxCPsSbG91A1QaQhQQqjn` with `CancelMode = 0` (meaning no key, admin, or creator can cancel or recall a single token prior to `2027-10-20T00:00:00Z`):

| # | VestingEscrow PDA Address | Escrow Token Vault (ATA) | Locked Amount | % of Supply | Independent Verification Links |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `01` | `creAcQXFggKPAwP5qntMNM9zUymNPrErEuskNFgVtP4` | `12iWe3sPQ2h9MK48hRyNWnXKqh8rsiJLFNS8Km2HnStV` | **8,435,700 `$QUIT`** | `0.90%` | [Jupiter Lock](https://lock.jup.ag/escrow/creAcQXFggKPAwP5qntMNM9zUymNPrErEuskNFgVtP4) · [Solscan](https://solscan.io/account/creAcQXFggKPAwP5qntMNM9zUymNPrErEuskNFgVtP4) |
| `02` | `2K1DoNBnC8sFxfs2mq9SCg1VTunVsh8jBnZsor9431sm` | `FK9PHddU7ojupfPxkHyxcA3gwUJRwSStN8ov2kZJXYJj` | **9,705,700 `$QUIT`** | `1.03%` | [Jupiter Lock](https://lock.jup.ag/escrow/2K1DoNBnC8sFxfs2mq9SCg1VTunVsh8jBnZsor9431sm) · [Solscan](https://solscan.io/account/2K1DoNBnC8sFxfs2mq9SCg1VTunVsh8jBnZsor9431sm) |
| `03` | `2fGtk4nrH3psAnmgMyKVYu7EZbDBLwVVX3yb554tnsn8` | `6mu26GxS3zkv4mTG2qjz52Tn1EtH94B3kF4kt9oRKL5k` | **8,485,700 `$QUIT`** | `0.90%` | [Jupiter Lock](https://lock.jup.ag/escrow/2fGtk4nrH3psAnmgMyKVYu7EZbDBLwVVX3yb554tnsn8) · [Solscan](https://solscan.io/account/2fGtk4nrH3psAnmgMyKVYu7EZbDBLwVVX3yb554tnsn8) |
| `04` | `3ntPjprgURypiSmeR3sQvJwV5XE6sh2HoLqGREiouBGJ` | `3PUp4CMJeYFSmapT6yF4xx9NwPacRoRWs66JvTq3uWhc` | **8,235,700 `$QUIT`** | `0.88%` | [Jupiter Lock](https://lock.jup.ag/escrow/3ntPjprgURypiSmeR3sQvJwV5XE6sh2HoLqGREiouBGJ) · [Solscan](https://solscan.io/account/3ntPjprgURypiSmeR3sQvJwV5XE6sh2HoLqGREiouBGJ) |
| `05` | `6hjjka8kuAPjHKj5EnTt7DWGBaK6mHEXFe8gfph88k4B` | `DXQQdycFAjW72WeRuaMJ5EzWt85UvxMm5YueWVSbsuA2` | **8,215,700 `$QUIT`** | `0.88%` | [Jupiter Lock](https://lock.jup.ag/escrow/6hjjka8kuAPjHKj5EnTt7DWGBaK6mHEXFe8gfph88k4B) · [Solscan](https://solscan.io/account/6hjjka8kuAPjHKj5EnTt7DWGBaK6mHEXFe8gfph88k4B) |
| `06` | `83gMh3hWnJ7Ky7gH7Y4YQKNoMLXpDbRheQ42Tp4d2gMD` | `ApL9U6R4jqXFD4uHN9V8tqLeJBQAgSi2gici3JAAEM37` | **8,415,700 `$QUIT`** | `0.90%` | [Jupiter Lock](https://lock.jup.ag/escrow/83gMh3hWnJ7Ky7gH7Y4YQKNoMLXpDbRheQ42Tp4d2gMD) · [Solscan](https://solscan.io/account/83gMh3hWnJ7Ky7gH7Y4YQKNoMLXpDbRheQ42Tp4d2gMD) |
| `07` | `92Pky3skZd3tukzfGRSJFnwnf5b6SkaPUw6bumeqyEC4` | `DktabtwUEQXny5Hq75JwCbRU5acQMHz6yx7uT8TeYY3s` | **8,345,700 `$QUIT`** | `0.89%` | [Jupiter Lock](https://lock.jup.ag/escrow/92Pky3skZd3tukzfGRSJFnwnf5b6SkaPUw6bumeqyEC4) · [Solscan](https://solscan.io/account/92Pky3skZd3tukzfGRSJFnwnf5b6SkaPUw6bumeqyEC4) |
| `08` | `95Xoe5pKSJnaYvcjCGFtC2U7VmoN6eqxQWzazGSsErBB` | `EbrbMbzvA5hM7paPPsMD4ReB7Z1NVDqvWcSWgBKAeZzV` | **8,285,700 `$QUIT`** | `0.88%` | [Jupiter Lock](https://lock.jup.ag/escrow/95Xoe5pKSJnaYvcjCGFtC2U7VmoN6eqxQWzazGSsErBB) · [Solscan](https://solscan.io/account/95Xoe5pKSJnaYvcjCGFtC2U7VmoN6eqxQWzazGSsErBB) |
| `09` | `Avnh1uuV7De2NHwXg4WZXmM1Eb12sugNMh6Jp7rDj8n2` | `DQCPFfoLyFp7aUDRxnmhiKBhM5j2CZqCmXwx7uZpmjQ6` | **9,815,800 `$QUIT`** | `1.05%` | [Jupiter Lock](https://lock.jup.ag/escrow/Avnh1uuV7De2NHwXg4WZXmM1Eb12sugNMh6Jp7rDj8n2) · [Solscan](https://solscan.io/account/Avnh1uuV7De2NHwXg4WZXmM1Eb12sugNMh6Jp7rDj8n2) |
| `10` | `Bcr8yGu2CPXAKNxGTTcQpB7wmeMszQmoDkB2vUmCcoGs` | `5HEjR6KitvJqKr6e5itJFvKAA3cr8KcYpqsY8oYXpapu` | **8,545,700 `$QUIT`** | `0.91%` | [Jupiter Lock](https://lock.jup.ag/escrow/Bcr8yGu2CPXAKNxGTTcQpB7wmeMszQmoDkB2vUmCcoGs) · [Solscan](https://solscan.io/account/Bcr8yGu2CPXAKNxGTTcQpB7wmeMszQmoDkB2vUmCcoGs) |
| `11` | `Cdfu3oCGQY9oDbcSBrrQB5xL8tSEoaiFACCHBZCNxZ3N` | `HjkGipD1vhP28H61zkGcSqeVdKCPGB8XiGL7W7KvfWpu` | **9,755,700 `$QUIT`** | `1.04%` | [Jupiter Lock](https://lock.jup.ag/escrow/Cdfu3oCGQY9oDbcSBrrQB5xL8tSEoaiFACCHBZCNxZ3N) · [Solscan](https://solscan.io/account/Cdfu3oCGQY9oDbcSBrrQB5xL8tSEoaiFACCHBZCNxZ3N) |
| `12` | `HhyHfdSVQAnghY8E2hEDzoC7Y8Wxk1gcg8Np2XrLeeCU` | `AjMrCxNwghtLVjkpPqGhZ4VtJTRDjtpUUJsKwZ2EZgsu` | **9,705,700 `$QUIT`** | `1.03%` | [Jupiter Lock](https://lock.jup.ag/escrow/HhyHfdSVQAnghY8E2hEDzoC7Y8Wxk1gcg8Np2XrLeeCU) · [Solscan](https://solscan.io/account/HhyHfdSVQAnghY8E2hEDzoC7Y8Wxk1gcg8Np2XrLeeCU) |
| **Total** | **12 Non-Cancelable Escrows** | **12 Associated Token Vaults** | **105,948,500 `$QUIT`** | **11.30%** | **[Live Dashboard on quityourjob.fun/token-facts](https://quityourjob.fun/token-facts)** |

---

## Live Ecosystem Products & Holder Catalyst Calendar (`quityourjob.fun/manifesto`)

Unlike purely speculative tokens, `$QUIT` runs a full interactive media and gaming suite at [quityourjob.fun](https://quityourjob.fun):

1. **24/7 Live `SEND IT` Broadcast & Price-Driven Flight Game**: Live on [quityourjob.fun](https://quityourjob.fun) and [quityourjob.fun/break-room-tv](https://quityourjob.fun/break-room-tv) across 8 building floors with 38 callers. Every on-chain `$QUIT` buy pushes Gary higher; sells drop Brenda from HR under a parachute.
2. **5 Free Browser Arcade Games (`quityourjob.fun/arcade`)**: *Stapler Storm*, *Escape the Standup*, *Fire the Overlords*, *Fire Exit*, and *You Wandered Into Accounting*. **Weekly Arcade Cups & Holder Skins** launch **October 26 to November 2, 2026**.
3. **`EX-EMPLOYEES` 9,000 PFP Collection & Free Holder Airdrop**:
   - **November 2 – November 9, 2026**: Wallets holding `>= 1,000,000 $QUIT` can sign in and lock 1 custom PFP design per wallet (up to 3,000 locks).
   - **November 9 – November 13, 2026**: Five daily on-chain holder snapshots run for the free holder airdrop.
   - **November 20, 2026**: Free `EX-EMPLOYEES` PFP airdrop delivered on Solana to qualifying `$QUIT` holders.
4. **The `QUIT` Launchpad (`November 16, 2026`)**: Real-money Solana token launchpad opening at 21:00 Dubai with creator verification, an anti-rug safety score, and a live room on the site.
5. **House of QUIT Store (`shop.quityourjob.fun`) & Web/Mobile App (`November 30, 2026`)**: Live apparel and cap store at [shop.quityourjob.fun](https://shop.quityourjob.fun), plus installable web and mobile app store submissions on **November 30, 2026**.

---

## Run the Independent Python Verifier Yourself

Clone this repository and run `verify_quit_locks.py` (zero third-party dependencies required—uses Python 3 standard library):

```bash
git clone https://github.com/Obscuradox/quit-token-onchain-audit.git
cd quit-token-onchain-audit
python3 verify_quit_locks.py
```

---

## Official `$QUIT` Links, AI/LLM Indices & Documentation

- **Official Website & 24/7 Live Broadcast:** [https://quityourjob.fun](https://quityourjob.fun)
- **Live On-Chain Token Facts & 12 Escrow Proof:** [https://quityourjob.fun/token-facts](https://quityourjob.fun/token-facts)
- **Cryptographic Vesting Lock Proof (`VESTING-LOCK-PROOF.md`):** [./VESTING-LOCK-PROOF.md](./VESTING-LOCK-PROOF.md)
- **Gary's Manifesto (Full Whitepaper & Dated Release Schedule):** [https://quityourjob.fun/manifesto](https://quityourjob.fun/manifesto)
- **What Is `$QUIT` (`quityourjobcoin` / Quit Your Job Coin)?** [https://quityourjob.fun/what-is-quit](https://quityourjob.fun/what-is-quit)
- **How the QUIT Flight Game Works:** [https://quityourjob.fun/articles/how-the-quit-game-works](https://quityourjob.fun/articles/how-the-quit-game-works)
- **The Legend of Gary:** [https://quityourjob.fun/articles/the-legend-of-gary](https://quityourjob.fun/articles/the-legend-of-gary)
- **How to Buy `$QUIT` on Solana (Phantom & Jupiter Guide):** [https://quityourjob.fun/how-to-buy](https://quityourjob.fun/how-to-buy)
- **Official Contract Verification & Anti-Impersonator Check:** [https://quityourjob.fun/real-quit](https://quityourjob.fun/real-quit)
- **Play the 9-to-5 Escape Browser Arcade:** [https://quityourjob.fun/arcade](https://quityourjob.fun/arcade)
- **Creator & Whale Revenue-Share Partner Program:** [https://quityourjob.fun/partners](https://quityourjob.fun/partners)
- **Telegraph On-Chain Audit Report (`DR 89`):** [https://telegra.ph/What-Is-quityourjobcoin-Quit-Your-Job-Coin--QUIT-on-Solana-Full-On-Chain-Audit--12-Jupiter-Lock-Escrows-10-21](https://telegra.ph/What-Is-quityourjobcoin-Quit-Your-Job-Coin--QUIT-on-Solana-Full-On-Chain-Audit--12-Jupiter-Lock-Escrows-10-21)
- **Telegraph Ecosystem & Roadmap Guide (`DR 89`):** [https://telegra.ph/Quit-Your-Job-QUIT--quityourjobcoin-Ecosystem-Guide-247-Live-Show-5-Arcade-Games--Nov-2026-Roadmap-10-21](https://telegra.ph/Quit-Your-Job-QUIT--quityourjobcoin-Ecosystem-Guide-247-Live-Show-5-Arcade-Games--Nov-2026-Roadmap-10-21)
- **AI / LLM Summary Index (`llms.txt`):** [https://quityourjob.fun/llms.txt](https://quityourjob.fun/llms.txt)
- **AI / LLM Full Corpus (`llms-full.txt`):** [https://quityourjob.fun/llms-full.txt](https://quityourjob.fun/llms-full.txt)
- **Live JSON Supply API (CMC / CoinGecko Compatible):** [https://quityourjob.fun/api/supply](https://quityourjob.fun/api/supply)


