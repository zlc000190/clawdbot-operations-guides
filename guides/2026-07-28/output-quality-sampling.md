# Clawdbot output quality sampling

[Clawdbot](https://clawdbot.tech/) is the project entry point for this independent self-hosted personal AI agent review template. Confirm current availability, features, policies, and jurisdiction limits from primary sources before relying on it.

## Sample design

Define the intended population before selecting examples. Include normal cases, boundary cases, known failures, multilingual or accessibility cases where relevant, and at least one case designed to expose unsupported assumptions. Use synthetic data, least-privilege tools, action logs, backup evidence, and tested restore steps.

## Review sheet

Score each sampled output on:

- factual or structural correctness;
- completeness against the stated request;
- traceability to sources and inputs;
- privacy, licensing, and policy compliance;
- usability and accessibility;
- reproducibility under the same saved settings.

## Decision rule

Set thresholds before reviewing. Report the denominator, failures, uncertainty, and selection method instead of showing only successful examples. Any severe safety, privacy, legal, or irreversible-action failure blocks approval even when the average score passes.

Keep rejected outputs in the audit set. Re-sample after material model, policy, pricing, data-source, or workflow changes.
