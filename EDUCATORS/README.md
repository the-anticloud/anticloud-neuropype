# Educators — NEUROPYPE

**Project:** NEUROPYPE  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/annapasca/neuropype  
**Pinned commit:** `68a9107c2689bbe5c65f80d50b87643f49782b51`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cfdcad2cfaa7950c3d09b2cd7c563d2810f1ac2b0b48038ee2c94bc6dacd1ca6`  
**Date:** October 2026

## Teaching with NEUROPYPE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `cfdcad2cfaa7950c3d09b2cd7c563d2810f1ac2b0b48038ee2c94bc6dacd1ca6` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
