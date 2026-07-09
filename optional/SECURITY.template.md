# <project-name>: Security

This document records the project's security expectations: what must be
protected, who can access it, what must not be exposed, and how security risks
are reviewed. Delete this file for projects where security notes are not useful.

Delete sections, rows, or examples that do not apply.

Related documents, if they exist:

- Project brief: <path-or-none>
- Plan: <path-or-none>
- Development guide: <path-or-none>
- Technology notes: <path-or-none>
- Storage notes: <path-or-none>
- Privacy notice: <path-or-none>
- Operations guide: <path-or-none>

## Security Summary

- Security owner: <person-or-team>
- Security status: <draft/active/needs-review/not-applicable>
- Data sensitivity: <none/low/medium/high/custom>
- Authentication required: <yes/no/partial/not-applicable>
- Authorization model: <roles/ownership/manual-approval/none/custom>
- External systems with security impact: <systems-or-none>
- Highest-risk area: <area-or-none>

## Protected Assets

List the things the project must protect. Use project language first; add
technical names only when useful.

| Asset | Why It Matters | Protection Needed |
|---|---|---|
| `<asset-1>` | <reason> | <protection> |
| `<asset-2>` | <reason> | <protection> |
| `<asset-3>` | <reason> | <protection> |

Protection rules:

- <protection-rule-1>
- <protection-rule-2>
- <protection-rule-3>

## Sensitive Data Rules

Use this section for security rules about sensitive data. Put public privacy
statements in the privacy notice, and put storage locations, retention, exports,
backups, and migrations in the storage notes.

| Data Or Material | Allowed Location | Logging Allowed | Sharing Allowed | Notes |
|---|---|---:|---:|---|
| `<data-or-material-1>` | <location-or-none> | <yes/no/redacted> | <yes/no/restricted> | <notes> |
| `<data-or-material-2>` | <location-or-none> | <yes/no/redacted> | <yes/no/restricted> | <notes> |
| `<data-or-material-3>` | <location-or-none> | <yes/no/redacted> | <yes/no/restricted> | <notes> |

Sensitive data rules:

- <sensitive-data-rule-1>
- <sensitive-data-rule-2>
- <sensitive-data-rule-3>

## Secrets And Credentials

Use this section for passwords, API keys, tokens, certificates, signing keys,
service accounts, and other credentials. Put local setup details and example
configuration names in the development guide.

| Secret Or Credential | Used For | Stored In | Rotation Or Review |
|---|---|---|---|
| `<secret-or-credential-1>` | <purpose> | <location> | <policy> |
| `<secret-or-credential-2>` | <purpose> | <location> | <policy> |

Secret rules:

- <secret-rule-1>
- <secret-rule-2>
- <secret-rule-3>

## Access Control

Use this section if people, roles, services, devices, or automated processes
have different access levels.

| Actor, Role, Or Process | Can Access | Must Not Access | Notes |
|---|---|---|---|
| `<actor-role-or-process-1>` | <allowed-access> | <restricted-access> | <notes> |
| `<actor-role-or-process-2>` | <allowed-access> | <restricted-access> | <notes> |

Access rules:

- <access-rule-1>
- <access-rule-2>
- <access-rule-3>

## Input, Output, And Boundary Rules

Use this section for rules about files, forms, commands, APIs, imports, exports,
generated output, external-system responses, or any other project boundary.

| Boundary | Main Risk | Rule |
|---|---|---|
| `<boundary-1>` | <risk> | <rule> |
| `<boundary-2>` | <risk> | <rule> |
| `<boundary-3>` | <risk> | <rule> |

Boundary rules:

- <boundary-rule-1>
- <boundary-rule-2>
- <boundary-rule-3>

## Logging And Error Handling

Use this section for what logs, diagnostics, analytics, traces, crash reports,
or error messages may include.

Allowed:

- <allowed-log-or-error-detail-1>
- <allowed-log-or-error-detail-2>
- <allowed-log-or-error-detail-3>

Not allowed:

- <disallowed-log-or-error-detail-1>
- <disallowed-log-or-error-detail-2>
- <disallowed-log-or-error-detail-3>

## External Code And Dependency Rules

Use this section for security expectations around packages, plugins, templates,
models, services, manual downloads, copied code, or other external materials.
Put the current technology inventory and update rhythm in the technology notes.

Rules:

- <external-code-or-dependency-rule-1>
- <external-code-or-dependency-rule-2>
- <external-code-or-dependency-rule-3>

Review triggers:

- <review-trigger-1>
- <review-trigger-2>

## Open Security Questions

- <question-1>
- <question-2>
- <question-3>
