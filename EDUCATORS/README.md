# Educators — DOKKU

**Project:** DOKKU  
**Category:** INFRA_DEVOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e7809be4f117f2357f8ecae14f3d5c4030c54141`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c`  
**Date:** October 2026

## Teaching with DOKKU

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
