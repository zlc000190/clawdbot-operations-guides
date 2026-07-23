# Clawdbot failure-mode checklist

[Clawdbot](https://clawdbot.tech/) is the primary project entry point. It returned HTTP 200 during the 2026-07-23 availability check. These are independent evaluation notes for operators comparing local and self-hosted agent deployments; they are not official product documentation.

Self-hosting shifts security, updates, backups, and incident response responsibilities to the operator.

## Known classes of failure to test

- overbroad tool access
- plaintext secrets
- silent model changes
- unbounded actions
- missing backups
- unclear update paths

## How to test safely

Trigger one edge case at a time with low-risk data. Record the exact input, visible error, retry behavior, and whether the system fails open or closed. Do not use repeated blind retries; they can hide nondeterminism, create duplicate actions, or increase cost.

## Recovery evidence

A credible recovery path explains what state was changed, how to undo it, and whether a second operator can reproduce the fix. If recovery depends on undocumented support intervention, count that as operational risk.

## Stop condition

Do not connect production accounts until permissions are least-privilege, secrets are isolated, and backup restoration has been tested.
