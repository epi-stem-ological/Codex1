# Codex1

Codex1 is a public AI-assisted software engineering starter kit for using Codex, Claude Code, ChatGPT, and similar coding agents with better structure, safer boundaries, clearer tasks, and higher-quality outputs.

This repository is intentionally public. It contains reusable, sanitized workflows only. It does not contain private personal data, employer-specific information, production credentials, customer data, financial records, or confidential project details.

## Mission

Codex1 turns AI-assisted coding from a loose chat experience into a repeatable engineering workflow.

The goal is to make agents better at:

- understanding the job to be done
- working from clear task specs
- producing reviewable changes
- respecting privacy and safety boundaries
- handing work off between tools
- documenting decisions
- improving quality through tests and acceptance criteria

## Relationship to Code-Wa7ad

Code-Wa7ad is the private command center and agentic engineering lab.

Codex1 is the public, sanitized, reusable layer.

In simple terms:

```text
Code-Wa7ad = private lab and command center
Codex1 = public starter kit and proof-of-work
```

Nothing private should be copied here unless it has been intentionally sanitized.

## Core Themes

1. **Prompt Contracts** - structured prompts that define role, task, inputs, constraints, output, and acceptance criteria.
2. **Task Specs** - issue-ready requirements that agents can execute without wandering.
3. **Agent Handoffs** - clean summaries for moving work between Codex, Claude Code, ChatGPT, and human review.
4. **Reviewability** - small changes, clear diffs, tests, and documentation.
5. **Public-Safe Examples** - fake data only, no private context leaks.
6. **Software Factory Habits** - repeatable scaffolding, issue templates, decision records, and release checklists.

## Repository Map

```text
.
├── AGENTS.md
├── README.md
├── docs/
│   ├── vision.md
│   ├── repo-map.md
│   ├── operating-principles.md
│   └── public-private-boundary.md
├── protocols/
│   ├── prompt-contract-protocol.md
│   ├── till-done-protocol.md
│   ├── pure-focus-protocol.md
│   └── agent-handoff-protocol.md
├── templates/
│   ├── prompt-contract.template.md
│   ├── task-spec.template.md
│   ├── agent-handoff.template.md
│   ├── decision-record.template.md
│   └── pr-review.template.md
├── examples/
│   ├── sample-task-spec.md
│   └── sample-agent-handoff.md
└── .github/
    └── ISSUE_TEMPLATE/
        ├── task-spec.md
        └── bug-report.md
```

## Suggested Use

Start with a task spec, then ask Codex or another coding agent to execute against that spec.

```text
Use templates/task-spec.template.md to define the work.
Use protocols/pure-focus-protocol.md to prevent scope drift.
Use protocols/agent-handoff-protocol.md when passing work to another tool or future session.
Use templates/pr-review.template.md to review the output.
```

## Public Safety Rules

Do not commit:

- API keys, tokens, secrets, passwords, or credentials
- real personal finance data
- real tax records
- private family information
- customer data
- employer-confidential material
- production infrastructure details
- private emails or messages
- crypto wallet secrets or seed phrases
- real personal contact lists

Use fake data, sample data, placeholders, or sanitized examples.

## Current Status

Early scaffold. The first goal is to create a practical public toolkit for agentic coding workflows.

## Roadmap

### Phase 1: Foundation

- README
- AGENTS.md
- task spec template
- prompt contract template
- handoff template
- pure focus protocol
- till done protocol

### Phase 2: Practical Examples

- example task specs
- example handoffs
- example review checklists
- small demo project scaffold

### Phase 3: Tooling

- CLI for generating task specs
- repo scaffolder
- prompt contract validator
- lightweight quality checklist runner

## License

MIT License, unless replaced later.
