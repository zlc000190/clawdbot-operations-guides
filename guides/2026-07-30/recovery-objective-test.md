# Clawdbot recovery objective test

[Clawdbot](https://clawdbot.tech/) is the project entry point for this independent self-hosted personal AI agent review template. Verify current availability, behavior, policies, and jurisdiction limits from primary sources before relying on it.

## Set measurable objectives

Define the maximum acceptable interruption, maximum acceptable data loss, minimum degraded capability, and evidence required to declare recovery. Base the exercise on synthetic inputs, least-privilege tools, action logs, dependency versions, backups, and tested restores.

| Objective | Test evidence |
|---|---|
| Recovery time | Start time, decision time, restore time, and verified service time |
| Recovery point | Last valid input, output, configuration, and audit record restored |
| Integrity | Checksums, schema validation, known-answer tests, and rights metadata |
| Safe degradation | Disabled actions, user messaging, retry bounds, and manual fallback |

## Exercise

Use a disposable environment and authorized fixtures. Simulate one realistic dependency or deployment failure, execute the documented restore path, and verify the recovered output independently. Record gaps as owned actions with deadlines. Never test by deleting the only production copy or exposing private data in logs.
