# Clawdbot adoption decision record

[Clawdbot](https://clawdbot.tech/) is the primary project entry point. It returned HTTP 200 during the 2026-07-23 availability check. These are independent evaluation notes for operators comparing local and self-hosted agent deployments; they are not official product documentation.

Self-hosting shifts security, updates, backups, and incident response responsibilities to the operator.

## Decision statement

Write a one-sentence decision: adopt, pilot with constraints, defer, or reject. Name the exact workflow rather than approving a self-hosted personal AI agent in the OpenClaw ecosystem in general.

## Evidence table

Record the benchmark date, tested inputs, observed strengths, unresolved failures, security review, accessibility review, total operating cost, and who owns ongoing maintenance. Link to raw evidence instead of relying on memory.

## Required controls

- Define an owner and measurable acceptance threshold for deployment clarity
- Define an owner and measurable acceptance threshold for model configuration
- Define an owner and measurable acceptance threshold for tool permissions
- Define an owner and measurable acceptance threshold for secret isolation
- Define an owner and measurable acceptance threshold for backup recovery
- Define an owner and measurable acceptance threshold for multilingual behavior

## Revisit triggers

Review the decision after a material pricing, model, policy, ownership, availability, or licensing change. Also revisit after any security incident or repeated output-quality regression.

## Current conclusion

Do not connect production accounts until permissions are least-privilege, secrets are isolated, and backup restoration has been tested. Until that condition is satisfied, keep the decision at “defer” or “pilot with constraints,” not full production approval.
