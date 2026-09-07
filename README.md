# Project Markdown Templates

A collection of Markdown templates for documenting software and other technical projects clearly and consistently.

The templates are designed to be filled in directly and adapted to the size, type, and stage of each project.

## What Is Included

* `core/`: templates that fit most projects.
* `optional/`: templates for projects that need additional planning, operations, security, storage, technology, or change-history documentation.
* `legal/`: public-facing legal and policy templates.
* `presets/`: suggested template sets for common project types.

## Core Templates

* `README.template.md`: public project overview.
* `PROJECT_BRIEF.template.md`: what the project is, who it is for, and why it exists.
* `PLAN.template.md`: implementation scope, structure, phases, and verification.
* `PROJECT_GUIDE.template.md`: shared project principles and working rules.
* `DEVELOPMENT.template.md`: local setup, commands, checks, debugging, and development workflow.

## Optional Templates

* `CHANGELOG.template.md`: release and change history.
* `DECISION_LOG.template.md`: durable decisions, alternatives, and tradeoffs.
* `TECHNOLOGY.template.md`: tools, platforms, versions, dependencies, and technical inventory.
* `STORAGE.template.md`: stored data, structure, migrations, retention, backups, and recovery expectations.
* `SECURITY.template.md`: secrets, access control, logging, sensitive data, and security boundaries.
* `ROADMAP.template.md`: future direction, priorities, milestones, and risks.
* `OPERATIONS.template.md`: publishing, recovery, monitoring, incidents, access, and operational runbooks.

## Legal Templates

* `PRIVACY.template.md`: public privacy notice.
* `TERMS.template.md`: terms of use.
* `NOTICE.template.md`: license notices, attribution, branding, and distribution notes.
* `DISCLAIMER.template.md`: risks, limitations, no-guarantee statements, and professional-advice disclaimers.

## Presets

Start with one preset, then add or remove templates as needed:

* `SMALL_PROJECT.md`
* `FULL_PROJECT.md`
* `EXPERIMENT.md`
* `LIBRARY.md`

## How To Use

1. Choose a preset from `presets/`.
2. Copy the templates listed in the preset into your project.
3. Remove `.template` from the copied filenames to create the final document names.
4. Fill in the relevant sections.
5. Delete sections, rows, and examples that do not apply to your project.
6. Add or remove documents as the project grows.
7. Keep each document focused on its own responsibility.

## Philosophy

These templates are intentionally generic.

A small project can keep more detail in the core documents, while a larger project can move durable decisions, storage rules, operations, security, and legal information into dedicated files.

The templates are intended as starting points rather than mandatory documentation standards. Use only the documents and sections that provide value for the project.
