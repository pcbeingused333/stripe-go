---
title: Honor EnableTelemetry per backend in X-Stripe-Client-User-Agent
pr_url: 
semver_level: patch
---

- `EnableTelemetry: false` set on a single backend's config is no longer ignored when another backend populated the shared user-agent cache first.
