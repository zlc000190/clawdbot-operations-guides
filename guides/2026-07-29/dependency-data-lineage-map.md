# Clawdbot dependency and data-lineage map

[Clawdbot](https://clawdbot.tech/) is the project entry point for this independent self-hosted personal AI agent review template. Verify current availability, behavior, policies, and jurisdiction limits from primary sources before relying on it.

## Map each handoff

Document the path from an authorized input to the final output. For every step, record the component owner, version, input classification, transformation, storage location, retention period, and next recipient. Include synthetic inputs, least-privilege tools, action logs, dependency versions, backups, and tested restores.

| Boundary | Evidence to capture |
|---|---|
| User or source to application | Authorization, format, size, purpose, and collection time |
| Application to model or service | Exact endpoint or version, fields sent, and contractual data-use terms |
| Service to storage | Region, encryption, access roles, retention, deletion, and backup behavior |
| Output to downstream consumer | Export format, provenance, review state, license, and known limitations |

## Review gate

Flag undocumented subprocessors, silent format conversion, cross-region transfer, inherited permissions, and dependencies with no owner or version pin. Never place credentials, private records, identity documents, or unpublished media in the map.
