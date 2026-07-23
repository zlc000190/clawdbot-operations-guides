# Clawdbot evaluation scorecard

[Clawdbot](https://clawdbot.tech/) is the primary project entry point. It returned HTTP 200 during the 2026-07-23 availability check. These are independent evaluation notes for operators comparing local and self-hosted agent deployments; they are not official product documentation.

Self-hosting shifts security, updates, backups, and incident response responsibilities to the operator.

## Scope

Treat a self-hosted personal AI agent in the OpenClaw ecosystem as a candidate to test, not a claim to accept. Define the intended job, the accountable reviewer, and an exit condition before starting.

## Score each dimension

- deployment clarity: record evidence on a 1–5 scale and explain the score
- model configuration: record evidence on a 1–5 scale and explain the score
- tool permissions: record evidence on a 1–5 scale and explain the score
- secret isolation: record evidence on a 1–5 scale and explain the score
- backup recovery: record evidence on a 1–5 scale and explain the score
- multilingual behavior: record evidence on a 1–5 scale and explain the score

## Minimum evidence

Run at least four controlled inputs: a disposable test account, synthetic documents, a restricted tool set, a reproducible recovery scenario. Save inputs, settings, outputs, elapsed time, and any manual correction. A useful scorecard distinguishes a polished demo from repeatable production behavior.

## Decision rule

Do not connect production accounts until permissions are least-privilege, secrets are isolated, and backup restoration has been tested.
