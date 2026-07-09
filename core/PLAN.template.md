# <project-name>: Engineering Plan

This plan turns a project goal into clear implementation steps. Fill it in with
plain language first, then add technical details where they are useful. Delete
sections, rows, or examples that do not apply to the project.

Related documents, if they exist:

- Project brief or source note: <path-or-none>
- Technology document: <path-or-none>
- Storage document: <path-or-none>
- Security or data-handling document: <path-or-none>
- Development workflow document: <path-or-none>
- Decision log: <path-or-none>

Main assumption for the first version:

> <who this first version is for, where they will use it, and what it should help them do>

## Implementation Scope

The first implementation should deliver:

- <deliverable-1>
- <deliverable-2>
- <deliverable-3>

This plan does not include:

- <out-of-scope-1>
- <out-of-scope-2>
- <out-of-scope-3>

## Initial Working Assumptions

Use this section for choices that help start implementation. Move long-term,
expensive, or debated decisions to the decision log.

- First thing people will use: <website/app/command/file/library/process/etc>.
- Main technology or runtime: <language/tool/runtime-or-none>.
- Data storage approach: <none/files/database/browser-storage/service/etc>.
- Login or access approach: <none/password/account-service/private-use/etc>.
- Where it will run first: <local-machine/server/cloud/device/browser/etc>.
- Main planning document or note: <document/path/section-or-none>.
- Where durable decisions are recorded: <document/path/section-or-none>.
- Where safety, privacy, or security rules are recorded: <document/path/section-or-none>.

## Current Project State

Already exists:

- <existing-piece-1>
- <existing-piece-2>
- <existing-piece-3>

Missing or not working yet:

- <limitation-1>
- <limitation-2>
- <limitation-3>

## Project Design

Describe the main parts of the project in plain language. Use the diagram only
if it helps. For a small project, this can be a short list instead of a system
diagram.

```text
<person-or-system-using-the-project>
  -> <main-entry-point>
  -> <main-project-part>
  -> <output-or-result>
```

Design rules that should stay consistent:

- <design-rule-1>
- <design-rule-2>
- <design-rule-3>

## Code Organization

Define the code organization that fits this project. Do not keep placeholder
rows for directories, packages, apps, or services the project does not use.

| Area Or Path | Responsibility | Owner |
|---|---|
| `<path-or-area-1>` | <responsibility> | <owner> |
| `<path-or-area-2>` | <responsibility> | <owner> |
| `<path-or-area-3>` | <responsibility> | <owner> |

Rules for keeping work organized:

- <boundary-rule-1>
- <boundary-rule-2>
- <boundary-rule-3>

## Target Project Shape

Describe the intended project shape only when it helps implementation. This can
be a directory tree, module list, package list, service map, notebook layout, or
single-file outline.

```text
<project-root-or-entry-point>
|-- <path-or-module-1>
|-- <path-or-module-2>
|-- <path-or-module-3>
`-- <path-or-module-4>
```

## First Usable Slice

Describe the smallest useful version someone can try. It should be small enough
to complete, review, and explain clearly.

User-visible workflow:

```text
<entry point>
  -> <user action>
  -> <project response>
  -> <saved or displayed result>
```

Acceptance criteria:

- <acceptance-1>
- <acceptance-2>
- <acceptance-3>

## Key Concepts

Define the important names, objects, inputs, outputs, files, screens,
or modules that people must understand before implementation starts.

| Concept | Meaning | Notes |
|---|---|---|
| `<name-1>` | <what it means> | <important detail> |
| `<name-2>` | <what it means> | <important detail> |
| `<name-3>` | <what it means> | <important detail> |

Rules for these concepts:

- <rule-1>
- <rule-2>
- <rule-3>

## Data And State Plan

Explain what information the project needs to keep, where it lives, and whether
it is temporary or saved. If the project does not store data, say so clearly.
Keep this section high-level. Put schema, migration, backup, retention, and
storage access details in the storage document if the project has
one.

| Data Or State | Where It Lives | Temporary Or Saved | Notes |
|---|---|---|---|
| `<data-or-state-1>` | <location> | <temporary/saved> | <notes> |
| `<data-or-state-2>` | <location> | <temporary/saved> | <notes> |
| `<data-or-state-3>` | <location> | <temporary/saved> | <notes> |

Data rules:

- <data-rule-1>
- <data-rule-2>
- <data-rule-3>

## Project Interactions

List the ways people or systems interact with the project. This may include
pages, API endpoints, files, forms, buttons, reports, imports, exports, or
scheduled jobs.

| Interaction | Input | Output | Notes |
|---|---|---|---|
| `<interaction-1>` | <input> | <output> | <notes> |
| `<interaction-2>` | <input> | <output> | <notes> |
| `<interaction-3>` | <input> | <output> | <notes> |

Interaction rules:

- <interaction-rule-1>
- <interaction-rule-2>
- <interaction-rule-3>

## External Dependencies

List anything outside the project that the implementation depends on. This can
include services, libraries, datasets, hardware, operating systems, people,
manual processes, design assets, or third-party accounts. If there are no
external dependencies, say so clearly.

| Dependency | Why It Is Needed | Fallback Or Alternative |
|---|---|---|
| `<dependency-1>` | <reason> | <fallback> |
| `<dependency-2>` | <reason> | <fallback> |

Dependency rules:

- <dependency-rule-1>
- <dependency-rule-2>

## Guardrails

The project must never:

- <guardrail-1>
- <guardrail-2>
- <guardrail-3>

If the project depends on outside facts, sources, dates, prices, regulations, or
third-party behavior, define how those claims are checked:

- Source missing: <what to do>
- Source stale: <what to do>
- Source conflicting: <what to do>

If source checking is not relevant, write:

> Not applicable.

## Phase Plan

### Planning

Acceptance:

- The project goal, first slice, and non-goals are clear.
- Code organization and ownership boundaries are clear where needed.
- Acceptance criteria are defined.

### First Usable Slice

Acceptance:

- <acceptance-1>
- <acceptance-2>
- <acceptance-3>

### <next-phase-name>

Acceptance:

- <acceptance-1>
- <acceptance-2>

### <later-phase-name>

Acceptance:

- <acceptance-1>
- <acceptance-2>

### <final-phase-name>

Acceptance:

- <acceptance-1>
- <acceptance-2>

## Verification Plan

Describe how people will know the implementation is correct.

Review steps:

- <review-step-1>
- <review-step-2>

Required sample cases:

- <sample-case-1>
- <sample-case-2>

## Implementation Risks

| Risk | Impact | Mitigation |
|---|---|---|
| <risk-1> | <impact> | <mitigation> |
| <risk-2> | <impact> | <mitigation> |
| <risk-3> | <impact> | <mitigation> |

## Open Implementation Questions

- <question-1>
- <question-2>
- <question-3>

## Near-Term Implementation Order

1. <step-1>
2. <step-2>
3. <step-3>
4. <step-4>
5. <step-5>
