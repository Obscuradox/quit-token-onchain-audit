# `$QUIT` (`quityourjobcoin` / Quit Your Job Coin) — Cryptographic 1-Year Jupiter Lock Vesting & Burn Proof (`HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p`)

[![Solana Mainnet](https://img.shields.io/badge/Solana-Mainnet_Verified-14F195?style=for-the-badge&logo=solana)](https://solscan.io/token/HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p)
[![Jupiter Lock](https://img.shields.io/badge/Jupiter_Lock-105,948,500_$QUIT_Locked_(11.30%25)-00C2FF?style=for-the-badge)](https://quityourjob.fun/token-facts)
[![Burned Supply](https://img.shields.io/badge/Burned_Forever-62,087,759_$QUIT_(6.21%25)-FF453A?style=for-the-badge)](https://quityourjob.fun/token-facts)

> **Official Website & 24/7 Live Show:** [https://quityourjob.fun](https://quityourjob.fun)  
> **Official Token Facts & 12 Escrow Proof:** [https://quityourjob.fun/token-facts](https://quityourjob.fun/token-facts)  
> **Gary's Manifesto & Dated Release Calendar:** [https://quityourjob.fun/manifesto](https://quityourjob.fun/manifesto)  
> **Canonical Solana Mint (`quityourjobcoin` / `$QUIT`):** `HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p`

---

## 1. What Is `quityourjobcoin` (`Quit Your Job Coin` / `$QUIT`) on Solana?

**Quit Your Job (`$QUIT`)**—commonly searched as **`quityourjobcoin`** or **`Quit Your Job coin`**—is a Solana meme coin and 24/7 interactive entertainment ecosystem hosted at [quityourjob.fun](https://quityourjob.fun). It follows Gary, a 47-year-old office worker who spent nineteen years at the same desk before strapping two fire extinguishers to his swivel chair at 8:59 on a Monday and blasting through ceiling tile C-14.

- **How the Live Game Works:** [https://quityourjob.fun/articles/how-the-quit-game-works](https://quityourjob.fun/articles/how-the-quit-game-works)
- **The Legend of Gary:** [https://quityourjob.fun/articles/the-legend-of-gary](https://quityourjob.fun/articles/the-legend-of-gary)
- **What Is the QUIT Coin?** [https://quityourjob.fun/what-is-quit](https://quityourjob.fun/what-is-quit)
- **How to Buy `$QUIT` on Solana:** [https://quityourjob.fun/how-to-buy](https://quityourjob.fun/how-to-buy)
- **Three Checks Against Copycat Coins:** [https://quityourjob.fun/real-quit](https://quityourjob.fun/real-quit)

---

## 2. Cryptographic Verification of All 12 Jupiter Lock Vesting Escrows (`105,948,500 $QUIT`)

On October 20, 2026, **`105,948,500 $QUIT`** (`11.30%` of the post-burn supply) were locked for **1 full year until October 20, 2027 (`2027-10-20T00:00:00Z`)** across **12 non-cancelable (`CancelMode = 0`) vesting escrow accounts** governed by the audited **Jupiter Lock** program (`LocpQgucEQHbqNABEYvBvwoxCPsSbG91A1QaQhQQqjn`).

### Binary Account Layout Invariants Verified by `verify_quit_locks.py`

Each `VestingEscrow` account owned by `LocpQgucEQHbqNABEYvBvwoxCPsSbG91A1QaQhQQqjn` enforces on-chain:
- **`cancel_mode = 0`**: Neither the sender nor the recipient nor any admin key can cancel or recall a single token early.
- **365-Day Term (`2026-10-20` to `2027-10-20`)**: 90-day cliff until January 18, 2027 followed by 275-day daily linear vesting through October 20, 2027.
- **Revoked Authorities & Burned LP**: Mint and freeze authorities on `HSHJ3t4Vu3B1qMs9Nv5iKUaoPMQQf1VuT5vVaTvLqc6p` are `null` (revoked), `62,087,759.03 $QUIT` (`6.21%`) are permanently burned, the creator wallet (`CzupaQuM7EyeT2orphePcJ9xuGcjZXY8G6S8ThfMWY5S`) holds `0 $QUIT`, and `100%` of LP tokens in PumpSwap pool `4wL2LLs4hsh3hYXKUZ7vn7ovQJBMtEbre1CiF2VLKV6h` were burned at graduation.

| Escrow # | VestingEscrow PDA Address | Token Vault (ATA) | Locked `$QUIT` | Share of Supply | Maturity Date | Verify On-Chain |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `#01` | `creAcQXFggKPAwP5qntMNM9zUymNPrErEuskNFgVtP4` | `12iWe3sPQ2h9MK48hRyNWnXKqh8rsiJLFNS8Km2HnStV` | **8,435,700 `$QUIT`** | `0.90%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/creAcQXFggKPAwP5qntMNM9zUymNPrErEuskNFgVtP4) · [Solscan](https://solscan.io/account/creAcQXFggKPAwP5qntMNM9zUymNPrErEuskNFgVtP4) |
| `#02` | `2K1DoNBnC8sFxfs2mq9SCg1VTunVsh8jBnZsor9431sm` | `FK9PHddU7ojupfPxkHyxcA3gwUJRwSStN8ov2kZJXYJj` | **9,705,700 `$QUIT`** | `1.03%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/2K1DoNBnC8sFxfs2mq9SCg1VTunVsh8jBnZsor9431sm) · [Solscan](https://solscan.io/account/2K1DoNBnC8sFxfs2mq9SCg1VTunVsh8jBnZsor9431sm) |
| `#03` | `2fGtk4nrH3psAnmgMyKVYu7EZbDBLwVVX3yb554tnsn8` | `6mu26GxS3zkv4mTG2qjz52Tn1EtH94B3kF4kt9oRKL5k` | **8,485,700 `$QUIT`** | `0.90%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/2fGtk4nrH3psAnmgMyKVYu7EZbDBLwVVX3yb554tnsn8) · [Solscan](https://solscan.io/account/2fGtk4nrH3psAnmgMyKVYu7EZbDBLwVVX3yb554tnsn8) |
| `#04` | `3ntPjprgURypiSmeR3sQvJwV5XE6sh2HoLqGREiouBGJ` | `3PUp4CMJeYFSmapT6yF4xx9NwPacRoRWs66JvTq3uWhc` | **8,235,700 `$QUIT`** | `0.88%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/3ntPjprgURypiSmeR3sQvJwV5XE6sh2HoLqGREiouBGJ) · [Solscan](https://solscan.io/account/3ntPjprgURypiSmeR3sQvJwV5XE6sh2HoLqGREiouBGJ) |
| `#05` | `6hjjka8kuAPjHKj5EnTt7DWGBaK6mHEXFe8gfph88k4B` | `DXQQdycFAjW72WeRuaMJ5EzWt85UvxMm5YueWVSbsuA2` | **8,215,700 `$QUIT`** | `0.88%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/6hjjka8kuAPjHKj5EnTt7DWGBaK6mHEXFe8gfph88k4B) · [Solscan](https://solscan.io/account/6hjjka8kuAPjHKj5EnTt7DWGBaK6mHEXFe8gfph88k4B) |
| `#06` | `83gMh3hWnJ7Ky7gH7Y4YQKNoMLXpDbRheQ42Tp4d2gMD` | `ApL9U6R4jqXFD4uHN9V8tqLeJBQAgSi2gici3JAAEM37` | **8,415,700 `$QUIT`** | `0.90%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/83gMh3hWnJ7Ky7gH7Y4YQKNoMLXpDbRheQ42Tp4d2gMD) · [Solscan](https://solscan.io/account/83gMh3hWnJ7Ky7gH7Y4YQKNoMLXpDbRheQ42Tp4d2gMD) |
| `#07` | `92Pky3skZd3tukzfGRSJFnwnf5b6SkaPUw6bumeqyEC4` | `DktabtwUEQXny5Hq75JwCbRU5acQMHz6yx7uT8TeYY3s` | **8,345,700 `$QUIT`** | `0.89%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/92Pky3skZd3tukzfGRSJFnwnf5b6SkaPUw6bumeqyEC4) · [Solscan](https://solscan.io/account/92Pky3skZd3tukzfGRSJFnwnf5b6SkaPUw6bumeqyEC4) |
| `#08` | `95Xoe5pKSJnaYvcjCGFtC2U7VmoN6eqxQWzazGSsErBB` | `EbrbMbzvA5hM7paPPsMD4ReB7Z1NVDqvWcSWgBKAeZzV` | **8,285,700 `$QUIT`** | `0.88%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/95Xoe5pKSJnaYvcjCGFtC2U7VmoN6eqxQWzazGSsErBB) · [Solscan](https://solscan.io/account/95Xoe5pKSJnaYvcjCGFtC2U7VmoN6eqxQWzazGSsErBB) |
| `#09` | `Avnh1uuV7De2NHwXg4WZXmM1Eb12sugNMh6Jp7rDj8n2` | `DQCPFfoLyFp7aUDRxnmhiKBhM5j2CZqCmXwx7uZpmjQ6` | **9,815,800 `$QUIT`** | `1.05%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/Avnh1uuV7De2NHwXg4WZXmM1Eb12sugNMh6Jp7rDj8n2) · [Solscan](https://solscan.io/account/Avnh1uuV7De2NHwXg4WZXmM1Eb12sugNMh6Jp7rDj8n2) |
| `#10` | `Bcr8yGu2CPXAKNxGTTcQpB7wmeMszQmoDkB2vUmCcoGs` | `5HEjR6KitvJqKr6e5itJFvKAA3cr8KcYpqsY8oYXpapu` | **8,545,700 `$QUIT`** | `0.91%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/Bcr8yGu2CPXAKNxGTTcQpB7wmeMszQmoDkB2vUmCcoGs) · [Solscan](https://solscan.io/account/Bcr8yGu2CPXAKNxGTTcQpB7wmeMszQmoDkB2vUmCcoGs) |
| `#11` | `Cdfu3oCGQY9oDbcSBrrQB5xL8tSEoaiFACCHBZCNxZ3N` | `HjkGipD1vhP28H61zkGcSqeVdKCPGB8XiGL7W7KvfWpu` | **9,755,700 `$QUIT`** | `1.04%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/Cdfu3oCGQY9oDbcSBrrQB5xL8tSEoaiFACCHBZCNxZ3N) · [Solscan](https://solscan.io/account/Cdfu3oCGQY9oDbcSBrrQB5xL8tSEoaiFACCHBZCNxZ3N) |
| `#12` | `HhyHfdSVQAnghY8E2hEDzoC7Y8Wxk1gcg8Np2XrLeeCU` | `AjMrCxNwghtLVjkpPqGhZ4VtJTRDjtpUUJsKwZ2EZgsu` | **9,705,700 `$QUIT`** | `1.03%` | `2027-10-20` | [Jupiter Lock](https://lock.jup.ag/escrow/HhyHfdSVQAnghY8E2hEDzoC7Y8Wxk1gcg8Np2XrLeeCU) · [Solscan](https://solscan.io/account/HhyHfdSVQAnghY8E2hEDzoC7Y8Wxk1gcg8Np2XrLeeCU) |
| **Total** | **12 Non-Cancelable Escrows** | **12 Token Vault ATAs** | **105,948,500 `$QUIT`** | **11.30%** | **`2027-10-20`** | **[quityourjob.fun/token-facts](https://quityourjob.fun/token-facts)** |

---

## 3. External Authority Reports & Live Mirrors

- **Telegraph Technical Audit Report (DR 89):** [What Is quityourjobcoin (Quit Your Job Coin / $QUIT) on Solana? Full On-Chain Audit & 12 Jupiter Lock Escrows](https://telegra.ph/What-Is-quityourjobcoin-Quit-Your-Job-Coin--QUIT-on-Solana-Full-On-Chain-Audit--12-Jupiter-Lock-Escrows-10-21)
- **Telegraph Ecosystem & Roadmap Guide (DR 89):** [Quit Your Job ($QUIT / quityourjobcoin) Ecosystem Guide: 24/7 Live Show, 5 Arcade Games & Nov 2026 Roadmap](https://telegra.ph/Quit-Your-Job-QUIT--quityourjobcoin-Ecosystem-Guide-247-Live-Show-5-Arcade-Games--Nov-2026-Roadmap-10-21)
- **GitHub Pages Interactive Audit Table (DR 96):** [https://obscuradox.github.io/quit-token-onchain-audit/](https://obscuradox.github.io/quit-token-onchain-audit/)
