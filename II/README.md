# Independent Insurance — DOKKU

**Project:** DOKKU  
**Category:** INFRA_DEVOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e7809be4f117f2357f8ecae14f3d5c4030c54141`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | DOKKU with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
