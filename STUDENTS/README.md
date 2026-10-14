# Students — CANLABCORE

**Project:** CANLABCORE  
**Category:** PSYCHOLOGY  
**Upstream:** https://github.com/canlab/CanlabCore  
**Pinned commit:** `5c4f6827d6937c3c16f2dc5f250fd0cc5889568d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `b4c6f59b2c9941716d42a44539c2d4ea4c46bde91811ec4c60585e11982cf308`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `5c4f6827d6937c3c16f2dc5f250fd0cc5889568d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `b4c6f59b2c9941716d42a44539c2d4ea4c46bde91811ec4c60585e11982cf308`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
