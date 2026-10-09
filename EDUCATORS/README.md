# Educators — BITCOIN

**Project:** BITCOIN  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/bitcoin/bitcoin  
**Pinned commit:** `7988380da987c0b860885853ace8149b84ac2ee8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e0106e7e680c4543fe7056301b2c9276ceccb045ed1abac69e838d2efa95595a`  
**Date:** October 2026

## Teaching with BITCOIN

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `e0106e7e680c4543fe7056301b2c9276ceccb045ed1abac69e838d2efa95595a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
