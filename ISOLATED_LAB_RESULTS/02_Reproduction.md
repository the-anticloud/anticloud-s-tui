# Reproduction — S_TUI

1. Environment: Windows, Python 3.12.10, runner version 1.0.0
2. `cd anticloud/`
3. `python tools\run_bench.py --quiet`  (exit 0 = all 16 PASS)
4. Compare `anticloud/BENCH.json` SHA3-256: `353ac94b4f7c9c54b560c5817d42390429c114842e70462461e9c73b0751f5a2`

The `anticloud/` overlay is a standalone copy of the anticloud_reference tree; the 16 checks run against it via `tools/run_bench.py`.
