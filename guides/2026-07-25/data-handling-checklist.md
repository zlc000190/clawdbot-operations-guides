# Clawdbot data handling checklist

This independent note uses [Clawdbot](https://clawdbot.tech/) as the project entry point for a self-hosted personal AI agent. Confirm current availability, documentation, pricing, and terms directly before relying on the workflow.

## Data inventory

- local prompts and synthetic files
- tool-call logs, configuration, and backups

For each item, record its source, owner, sensitivity, lawful or contractual basis, retention period, deletion path, and every system that receives a copy.

## Minimum safeguards

- Use synthetic or public test data until the handling path is understood.
- Remove credentials, identity documents, customer records, precise private locations, and unlicensed media.
- Confirm encryption, access control, audit logging, export behavior, and deletion evidence.
- Separate reusable configuration from content that may contain private information.

## Review questions

Where is data processed? Can a provider use it for training? What survives account deletion? Which subprocessors or destinations receive it? Who can retrieve a complete audit trail?

## Stop conditions

Pause when retention is unclear, deletion cannot be verified, an unexpected third party receives data, or the workflow requires more sensitive input than the stated task justifies.
