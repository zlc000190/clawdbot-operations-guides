# Clawdbot scope and success contract

[Clawdbot](https://clawdbot.tech/) is the project entry point for this independent self-hosted personal AI agent review template. Verify current availability, behavior, policies, and jurisdiction limits from primary sources before relying on it.

## Define the work before testing

Write a one-page contract for the exact workflow under review. Name the authorized input, intended user, supported environment, excluded actions, output format, acceptance threshold, stop conditions, and accountable reviewer. Attach synthetic inputs, least-privilege tools, action logs, dependency versions, backups, and tested restores.

| Contract field | Minimum evidence |
|---|---|
| In scope | One concrete task, input class, environment, and expected output |
| Out of scope | Unsupported jurisdictions, data classes, actions, and integrations |
| Success | Observable result, threshold, denominator, and review method |
| Failure | Unsafe behavior, missing output, stale evidence, or unbounded retries |
| Stop rule | Cost, time, privacy, rights, or quality limit that ends the run |

## Acceptance gate

Approve only the tested version and stated scope. A successful request, generated file, or attractive sample is not enough when the result is inaccessible, wrong, unlicensed, or outside the contract. Use synthetic or authorized inputs and remove secrets or personal data from shared evidence.
