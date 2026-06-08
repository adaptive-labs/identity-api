---
category: architecture
title: Identity API — Architecture
description: Customer and staff identity, login, and account management.
related_teams:
  - identity-access
---

# Identity API

Customer and staff identity, login, and account management.

## Overview

`identity-api` is a api owned by the Identity & Access team. It runs in production as a tier-critical service.

## Dependencies

It talks to:
- `sso-bridge`
- `user-profile`
