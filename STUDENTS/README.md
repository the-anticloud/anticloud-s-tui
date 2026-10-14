# Students — S_TUI

**Project:** S_TUI  
**Category:** LAPTOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `2bdd1d6a6369de0e8c68132ea4539e9abd9e14a8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `fe9051a4f1274cbf28d0f60e2e785483d12cbb7016f5e5852ef92faf3e41ad2d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2bdd1d6a6369de0e8c68132ea4539e9abd9e14a8`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `fe9051a4f1274cbf28d0f60e2e785483d12cbb7016f5e5852ef92faf3e41ad2d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
