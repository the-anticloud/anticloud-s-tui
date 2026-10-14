# Educators — S_TUI

**Project:** S_TUI  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `2bdd1d6a6369de0e8c68132ea4539e9abd9e14a8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fe9051a4f1274cbf28d0f60e2e785483d12cbb7016f5e5852ef92faf3e41ad2d`  
**Date:** October 2026

## Teaching with S_TUI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `fe9051a4f1274cbf28d0f60e2e785483d12cbb7016f5e5852ef92faf3e41ad2d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
