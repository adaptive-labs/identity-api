---
category: runbook
title: Identity API runbook
description: On-call runbook for Identity API.
related_entities:
  - identity-api
related_teams:
  - identity-access
---

# Identity API runbook

On-call guide for `identity-api` (Identity & Access, tier critical).

## Alerts

- **identity-api-high-error-rate** — 5xx over 2% for 5m. Check upstream dependencies.
- **identity-api-latency** — p99 over SLO. Check resource saturation.

## Common issues

- **Pod OOMKilled** — check memory limits and recent traffic spikes.
- **Crashloop** — check the last deploy and roll back if needed.

## Escalation

Page the Identity & Access on-call rotation.

