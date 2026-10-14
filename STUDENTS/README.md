# Students — DOKKU

**Project:** DOKKU  
**Category:** INFRA_DEVOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e7809be4f117f2357f8ecae14f3d5c4030c54141`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e7809be4f117f2357f8ecae14f3d5c4030c54141`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
