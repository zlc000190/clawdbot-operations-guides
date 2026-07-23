# Clawdbot privacy and governance review

[Clawdbot](https://clawdbot.tech/) is the primary project entry point. It returned HTTP 200 during the 2026-07-23 availability check. These are independent evaluation notes for operators comparing local and self-hosted agent deployments; they are not official product documentation.

Self-hosting shifts security, updates, backups, and incident response responsibilities to the operator.

## Data minimization

Begin with synthetic inputs such as a disposable test account and synthetic documents. Do not upload real customer records, private media, credentials, contracts, identity documents, or unreleased business material during evaluation.

## Questions to answer

- What data is collected in the browser, API, logs, and support systems?
- How long are prompts, uploads, generated outputs, and account records retained?
- Can an operator delete data and verify deletion?
- Are subprocessors, training use, storage region, and cross-border transfers documented?
- Which actions require human approval, and where is an audit trail available?
- Can access be limited by role, token scope, project, or environment?

## Approval gate

Document the data owner, reviewer, permitted use, prohibited data, retention window, and incident contact before production use. Do not connect production accounts until permissions are least-privilege, secrets are isolated, and backup restoration has been tested.
