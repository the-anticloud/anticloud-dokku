# How to Update — DOKKU

**Project:** `DOKKU`
**Category:** INFRA_DEVOPS
**Domain:** infrastructure and DevOps
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
DOKKU --version
DOKKU check-update
```

### Applying Updates
```bash
pip install --upgrade DOKKU
```

### Rolling Back
```bash
pip install DOKKU==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
