# Ethics — S_TUI

**Project:** S_TUI  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `2bdd1d6a6369de0e8c68132ea4539e9abd9e14a8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fe9051a4f1274cbf28d0f60e2e785483d12cbb7016f5e5852ef92faf3e41ad2d`  
**Date:** October 2026

## Position

S_TUI is packaged for offline deployment with a verifiable audit trail. The
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
