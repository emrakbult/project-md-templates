# Project MD Templates

A collection of Markdown templates for documenting projects clearly. The
templates are meant to be filled in by humans and adapted to the size, type, and stage of each project.

## What Is Included

- `core/`: templates that fit most projects.
- `optional/`: templates for projects that need extra planning, operations,
  security, storage, technology, or change-history notes.
- `legal/`: public-facing legal and policy templates.
- `presets/`: suggested template sets for common project types.

## Core Templates

- `README.template.md`: public project overview.
- `PROJECT_BRIEF.template.md`: what the project is, who it is for, and why it
  exists.
- `PLAN.template.md`: implementation scope, structure, phases, and verification.
- `PROJECT_GUIDE.template.md`: shared project principles and working rules.
- `DEVELOPMENT.template.md`: local setup, commands, checks, debugging, and
  sharing workflow.

## Optional Templates

- `CHANGELOG.template.md`: release or change history.
- `DECISION_LOG.template.md`: durable decisions and tradeoffs.
- `TECHNOLOGY.template.md`: tools, platforms, versions, and technical inventory.
- `STORAGE.template.md`: stored data, structure, migration, retention, backup,
  and recovery expectations.
- `SECURITY.template.md`: secrets, access, logging, sensitive data, and boundary
  rules.
- `ROADMAP.template.md`: future direction, priorities, milestones, and risks.
- `OPERATIONS.template.md`: publishing, recovery, monitoring, incidents, access,
  and runbooks.

## Legal Templates

- `PRIVACY.template.md`: public privacy notice.
- `TERMS.template.md`: terms of use.
- `NOTICE.template.md`: license notices, attribution, branding, and distribution
  notes.
- `DISCLAIMER.template.md`: risks, limits, no guarantees, and professional-advice
  disclaimers.

## Presets

Start with one preset, then add or remove templates as needed:

- `SMALL_PROJECT.md`
- `FULL_PROJECT.md`
- `EXPERIMENT.md`
- `LIBRARY.md`

## How To Use

1. Pick a preset from `presets/`.
2. Copy the listed templates into your project.
3. Rename copied files by removing `.template` if you want final document names.
4. Delete sections, rows, and examples that do not apply.
5. Keep each document focused on its own responsibility.

These templates are intentionally generic. A small project can keep more detail
in the core files, while a larger project can move durable decisions, storage
rules, operations, security, and legal details into dedicated documents.
