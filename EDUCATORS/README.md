# Educators — CANLABCORE

**Project:** CANLABCORE  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/canlab/CanlabCore  
**Pinned commit:** `5c4f6827d6937c3c16f2dc5f250fd0cc5889568d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b4c6f59b2c9941716d42a44539c2d4ea4c46bde91811ec4c60585e11982cf308`  
**Date:** October 2026

## Teaching with CANLABCORE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `b4c6f59b2c9941716d42a44539c2d4ea4c46bde91811ec4c60585e11982cf308` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
