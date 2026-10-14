# Students — BITCOIN

**Project:** BITCOIN  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/bitcoin/bitcoin  
**Pinned commit:** `7988380da987c0b860885853ace8149b84ac2ee8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e0106e7e680c4543fe7056301b2c9276ceccb045ed1abac69e838d2efa95595a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7988380da987c0b860885853ace8149b84ac2ee8`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `e0106e7e680c4543fe7056301b2c9276ceccb045ed1abac69e838d2efa95595a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
