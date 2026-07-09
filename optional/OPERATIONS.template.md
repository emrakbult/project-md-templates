# <project-name>: Operations

This document explains how the project is run, published, monitored, recovered,
and supported after other people or systems rely on it. Delete this file for
projects that do not need operational notes.

Delete sections, rows, or examples that do not apply.

Related documents, if they exist:

- Project brief: <path-or-none>
- Development guide: <path-or-none>
- Technology notes: <path-or-none>
- Storage notes: <path-or-none>
- Security or privacy notes: <path-or-none>
- Changelog: <path-or-none>

## Operations Summary

- Operations owner: <person-or-team>
- Operational status: <draft/active/paused/retired/not-applicable>
- Main operating context: <local/shared/public/hosted/distributed/custom>
- Support contact or channel: <contact-or-none>
- Review rhythm: <none/weekly/monthly/per-release/custom>

## Operating Contexts

Use this section for environments, release channels, devices, accounts,
locations, hosted systems, shared folders, stores, registries, or other places
where the project runs or is made available.

| Context | Purpose | Location Or Access | Data Sensitivity | Owner |
|---|---|---|---|---|
| `<context-1>` | <purpose> | <location-or-access> | <none/low/medium/high/custom> | <owner> |
| `<context-2>` | <purpose> | <location-or-access> | <none/low/medium/high/custom> | <owner> |
| `<context-3>` | <purpose> | <location-or-access> | <none/low/medium/high/custom> | <owner> |

Context rules:

- <context-rule-1>
- <context-rule-2>
- <context-rule-3>

## Publish, Release, Or Deploy

Use this section for the operational process that makes a version available.
Local development commands belong in the development guide.

- Release or deployment method: <method-or-none>
- Approval needed: <who-or-none>
- Release frequency: <on-demand/scheduled/continuous/custom/none>
- Release notes or changelog expectation: <expectation-or-none>

Operational steps:

```bash
<release-or-deploy-command-or-none>
```

Manual steps:

- <manual-step-1>
- <manual-step-2>
- <manual-step-3>

## Rollback And Recovery

Describe how to return to a known-good state when a release, publish, deploy,
data change, configuration change, or operational process fails.

- Rollback approach: <approach-or-none>
- Recovery owner: <person-or-team>
- Recovery time expectation: <expectation-or-none>
- Known limitations: <limitations-or-none>

Rollback or recovery steps:

```bash
<rollback-or-recovery-command-or-none>
```

Manual recovery steps:

- <manual-recovery-step-1>
- <manual-recovery-step-2>

## Monitoring And Health

Use this section for signals that show whether the project is working as
expected. Delete it if the project does not have ongoing monitoring.

| Signal | Where To Check | Healthy State | Owner |
|---|---|---|---|
| `<signal-1>` | <location/tool/process> | <healthy-state> | <owner> |
| `<signal-2>` | <location/tool/process> | <healthy-state> | <owner> |
| `<signal-3>` | <location/tool/process> | <healthy-state> | <owner> |

Alert or review rules:

- <alert-or-review-rule-1>
- <alert-or-review-rule-2>
- <alert-or-review-rule-3>

## Logs, Reports, And Diagnostics

Use this section for where operational information can be checked. Put sensitive
logging rules in the security notes.

| Output | Location | Purpose | Retention Or Cleanup |
|---|---|---|---|
| `<output-1>` | <location> | <purpose> | <policy-or-none> |
| `<output-2>` | <location> | <purpose> | <policy-or-none> |

Diagnostic rules:

- <diagnostic-rule-1>
- <diagnostic-rule-2>

## Backup And Restore Operations

Use this section for restore runbooks and operational responsibilities. Put
storage expectations, retention policy, and backup strategy in the storage
notes.

- Backup owner: <person-or-team-or-none>
- Restore owner: <person-or-team-or-none>
- Restore test rhythm: <none/monthly/quarterly/per-release/custom>

Restore steps:

```bash
<restore-command-or-none>
```

Manual restore steps:

- <manual-restore-step-1>
- <manual-restore-step-2>

## Incident Or Issue Response

Use this section when the project needs a clear response process for outages,
broken releases, data exposure, support incidents, or other operational issues.

| Level | Meaning | Response |
|---|---|---|
| `<level-1>` | <meaning> | <response> |
| `<level-2>` | <meaning> | <response> |
| `<level-3>` | <meaning> | <response> |

Response steps:

- <response-step-1>
- <response-step-2>
- <response-step-3>

## Operational Access

Use this section for access needed to operate, publish, recover, or support the
project. Put security policy and sensitive access rules in the security notes.

| System Or Place | Access Needed | Who Has Access | Review Rhythm |
|---|---|---|---|
| `<system-or-place-1>` | <access-needed> | <person-role-or-team> | <rhythm-or-none> |
| `<system-or-place-2>` | <access-needed> | <person-role-or-team> | <rhythm-or-none> |

Operational access rules:

- <operational-access-rule-1>
- <operational-access-rule-2>

## Runbooks

Use this section for short links or commands people need during real operation.

| Runbook | When To Use | Link, Command, Or Location |
|---|---|---|
| `<runbook-1>` | <condition> | <link-command-or-location> |
| `<runbook-2>` | <condition> | <link-command-or-location> |
| `<runbook-3>` | <condition> | <link-command-or-location> |

## Open Operations Questions

- <question-1>
- <question-2>
- <question-3>
