# Ethics — NEUROPYPE

**Project:** NEUROPYPE  
**Category:** BRAIN_COMPUTER_INTERFACE  
**Upstream:** https://github.com/annapasca/neuropype  
**Pinned commit:** `68a9107c2689bbe5c65f80d50b87643f49782b51`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cfdcad2cfaa7950c3d09b2cd7c563d2810f1ac2b0b48038ee2c94bc6dacd1ca6`  
**Date:** October 2026

## Position

NEUROPYPE is packaged for offline deployment with a verifiable audit trail. The
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
