# Ethics — BITCOIN

**Project:** BITCOIN  
**Category:** CRYPTOCURRENCY  
**Upstream:** https://github.com/bitcoin/bitcoin  
**Pinned commit:** `7988380da987c0b860885853ace8149b84ac2ee8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e0106e7e680c4543fe7056301b2c9276ceccb045ed1abac69e838d2efa95595a`  
**Date:** October 2026

## Position

BITCOIN is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
