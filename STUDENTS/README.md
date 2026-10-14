# Students — NEUROPYPE

**Project:** NEUROPYPE  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/annapasca/neuropype  
**Pinned commit:** `68a9107c2689bbe5c65f80d50b87643f49782b51`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cfdcad2cfaa7950c3d09b2cd7c563d2810f1ac2b0b48038ee2c94bc6dacd1ca6`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `68a9107c2689bbe5c65f80d50b87643f49782b51`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `cfdcad2cfaa7950c3d09b2cd7c563d2810f1ac2b0b48038ee2c94bc6dacd1ca6`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
