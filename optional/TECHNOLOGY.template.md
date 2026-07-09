# <project-name>: Technology

This document records the current technology choices for the project. Use it as
an inventory of tools, platforms, versions, and technical requirements. Put the
reasoning for important choices in the decision log.

Delete sections, rows, or examples that do not apply.

Related documents, if they exist:

- Development guide: <path-or-none>
- Plan: <path-or-none>
- Storage notes: <path-or-none>
- Security or privacy notes: <path-or-none>
- Decision log: <path-or-none>

## Technology Summary

| Area | Current Choice | Status | Notes |
|---|---|---|---|
| Language | <language-or-none> | <planned/active/locked/replacing> | <notes> |
| Runtime or platform | <runtime-or-platform> | <planned/active/locked/replacing> | <notes> |
| Package or dependency manager | <tool-or-none> | <planned/active/locked/replacing> | <notes> |
| User interface | <framework/tool/none> | <planned/active/locked/replacing> | <notes> |
| Data storage | <tool/format/none> | <planned/active/locked/replacing> | <notes> |
| Testing or verification | <tool/process/none> | <planned/active/locked/replacing> | <notes> |
| Build or packaging | <tool/process/none> | <planned/active/locked/replacing> | <notes> |
| Deployment or distribution | <target/process/none> | <planned/active/locked/replacing> | <notes> |

## Runtime And Tools

| Tool | Version Or Range | Purpose | Required |
|---|---|---|---:|
| `<tool-1>` | <version-or-range> | <purpose> | <yes/no> |
| `<tool-2>` | <version-or-range> | <purpose> | <yes/no> |
| `<tool-3>` | <version-or-range> | <purpose> | <yes/no> |

Tooling rules:

- <tooling-rule-1>
- <tooling-rule-2>
- <tooling-rule-3>

## Application Or Project Surfaces

Use this section for apps, command-line tools, libraries, documents, datasets,
services, packages, or any other surface the project exposes.

| Surface | Technology | Notes |
|---|---|---|
| `<surface-1>` | <technology> | <notes> |
| `<surface-2>` | <technology> | <notes> |
| `<surface-3>` | <technology> | <notes> |

## Data, Storage, Or File Formats

Keep this section high-level. Put schema, migrations, retention, backups, and
access rules in the storage notes if the project has them.

| Data Or Format | Technology | Notes |
|---|---|---|
| `<data-or-format-1>` | <technology-or-none> | <notes> |
| `<data-or-format-2>` | <technology-or-none> | <notes> |

## Dependencies

List important runtime, build, external, or manual dependencies. Detailed update
commands belong in the development guide.

| Dependency | Purpose | Update Policy |
|---|---|---|
| `<dependency-1>` | <purpose> | <policy> |
| `<dependency-2>` | <purpose> | <policy> |

## Compatibility

- Supported platforms: <platforms-or-none>
- Supported runtimes or versions: <versions-or-none>
- Supported browsers, devices, or environments: <targets-or-none>
- Known unsupported targets: <targets-or-none>

## Build, Package, Or Distribution

Use this section to name the tools or targets. Put exact commands in the
development guide.

- Build tool or process: <tool-or-process>
- Package format: <format-or-none>
- Distribution target: <target-or-none>
- Release output location: <path-or-none>

## Upgrade Policy

- Dependency update rhythm: <none/manual/weekly/monthly/per-release/custom>
- Security update policy: <policy-or-none>
- Breaking change policy: <policy-or-none>
- Deprecated tools to avoid: <tools-or-none>

## Open Technology Questions

- <question-1>
- <question-2>
- <question-3>
