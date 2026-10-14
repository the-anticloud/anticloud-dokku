# Ethics — DOKKU

**Project:** DOKKU  
**Category:** INFRA_DEVOPS  
**Upstream:** see BENCH.json  
**Pinned commit:** `e7809be4f117f2357f8ecae14f3d5c4030c54141`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `25fbe2e957631328bd6f52fff4533069029aab0f019e476d0cd2ff744ce2e25c`  
**Date:** October 2026

## Position

DOKKU is packaged for offline deployment with a verifiable audit trail. The
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
