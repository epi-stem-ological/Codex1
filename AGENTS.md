# AGENTS.md

## Repository Identity

Codex1 is a public AI-assisted software engineering starter kit for building better workflows with Codex, Claude Code, ChatGPT, and similar coding agents.

This repo is public by design. Treat every file as something that could be read by strangers, employers, recruiters, collaborators, and future clients.

## Prime Directive

Build reusable public-safe artifacts that improve AI-assisted software engineering.

Every contribution should improve at least one of the following:

1. task clarity
2. coding-agent reliability
3. reviewability
4. privacy and safety boundaries
5. handoff quality
6. repeatable software-factory habits
7. public proof-of-work

## Public Safety Rules

Never commit:

- secrets, tokens, API keys, passwords, or credentials
- real personal financial data
- real tax records
- private family details
- private contact lists
- employer-confidential information
- customer data
- production infrastructure details
- private emails or messages
- crypto seed phrases, wallet secrets, or private addresses
- non-sanitized screenshots

Use only fake data, sample data, generic examples, or intentionally sanitized content.

## Style Rules

- Prefer plain Markdown before code.
- Prefer small reusable templates over large abstract essays.
- Prefer concrete examples over vague principles.
- Prefer public-safe language.
- Avoid hype.
- Avoid claiming a workflow is proven unless examples or tests support it.
- Label opinion, inference, and evidence clearly when relevant.

## Coding Rules

When code is added:

- keep it simple
- include setup instructions
- include tests for logic-heavy code
- avoid unnecessary dependencies
- use readable names
- document assumptions
- update README if behavior changes

## Folder Routing

Use this routing logic:

- Agent behavior and workflow rules: `protocols/`
- Reusable blank artifacts: `templates/`
- Filled-in fake examples: `examples/`
- Explanatory material: `docs/`
- GitHub issue templates: `.github/ISSUE_TEMPLATE/`

## Definition of Done

A change is done when:

- it is public-safe
- it has a clear purpose
- it fits the repo map
- it improves reusability
- examples use fake data
- future agents can understand it without extra context

## Agent Workflow

Before editing:

1. Read `README.md`.
2. Read this file.
3. Identify the target folder.
4. Make the smallest useful change.
5. Avoid unrelated cleanup.

After editing:

1. Summarize what changed.
2. List assumptions.
3. List next recommended tasks.
4. Flag privacy or public-safety concerns.
