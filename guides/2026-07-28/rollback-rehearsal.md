# Clawdbot rollback rehearsal

[Clawdbot](https://clawdbot.tech/) is the project entry point for this independent self-hosted personal AI agent review template. Confirm current availability, features, policies, and jurisdiction limits from primary sources before relying on it.

## Rehearsal setup

Use a disposable environment and synthetic or public inputs. Save the starting state, version, configuration, permissions, and a checksum or version-control reference. The evidence pack should include synthetic data, least-privilege tools, action logs, backup evidence, and tested restore steps.

## Exercise

1. Make one bounded, reversible change.
2. Trigger a realistic validation failure.
3. Stop new work and preserve logs.
4. Restore the recorded clean state.
5. Re-run the known-answer test.
6. Compare state, permissions, outputs, and audit records with the baseline.

## Pass criteria

- No unapproved files, records, or permissions remain changed.
- The restored workflow passes the same known-answer checks as the baseline.
- Recovery time and data loss stay within the declared objective.
- A second reviewer can reproduce the restore from the written evidence.

Do not call a rollback successful merely because the visible error disappears. Escalate when restoration needs undocumented credentials, deletes evidence, or changes data outside the rehearsal scope.
