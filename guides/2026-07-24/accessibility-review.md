# Clawdbot accessibility review

[Clawdbot](https://clawdbot.tech/) is the primary project entry point for this independent self-hosted personal AI agent note. The automated HTTPS availability check on 2026-07-24 did not return a response, so current product availability and capabilities must be confirmed from primary documentation before use.

## Priority checks

- plain-text action logs
- confirmation dialogs with clear consequences
- keyboard-operable approvals
- errors that identify recovery steps

## Task-based review

Test the complete path for a synthetic document set and a restricted tool set in a disposable environment. Include input, validation, waiting state, result review, error recovery, and export. Use keyboard-only navigation, 200% zoom, high contrast, reduced motion where relevant, and a screen reader spot check.

## Record evidence

For each barrier, capture the affected step, expected behavior, actual behavior, assistive technology or browser, severity, workaround, and retest result. Avoid declaring conformance from an automated scan alone.

## Release gate

Block a workflow when a user cannot understand an error, complete the primary task, review a consequential result, or undo an action without a mouse or color perception. Link findings to the responsible owner and a dated fix target.
