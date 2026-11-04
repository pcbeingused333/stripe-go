---
title: Send an Idempotency-Key on RawRequest POSTs with nil params
pr_url: 
semver_level: patch
---

- Generate an `Idempotency-Key` for `RawRequest` write requests made with nil params, so they are no longer retried without one.
