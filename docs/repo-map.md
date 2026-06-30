# Repository Map

```text
.
├── AGENTS.md
├── CONTRIBUTING.md
├── README.md
├── docs/
│   ├── vision.md
│   ├── repo-map.md
│   ├── operating-principles.md
│   ├── public-private-boundary.md
│   ├── public-readiness-checklist.md
│   └── phase-1-roadmap.md
├── protocols/
│   ├── prompt-contract-protocol.md
│   ├── till-done-protocol.md
│   ├── pure-focus-protocol.md
│   ├── agent-handoff-protocol.md
│   ├── model-routing-protocol.md
│   └── reviewability-protocol.md
├── templates/
│   ├── prompt-contract.template.md
│   ├── task-spec.template.md
│   ├── agent-handoff.template.md
│   ├── decision-record.template.md
│   ├── pr-review.template.md
│   ├── context-capsule.template.md
│   ├── project-brief.template.md
│   └── public-readiness-checklist.template.md
├── examples/
│   ├── sample-task-spec.md
│   ├── sample-agent-handoff.md
│   ├── sample-prompt-contract.md
│   └── sample-pr-review.md
└── .github/
    ├── pull_request_template.md
    └── ISSUE_TEMPLATE/
        ├── task-spec.md
        └── bug-report.md
```

## Folder Purposes

### `docs/`

Explains the philosophy, repo boundaries, operating principles, public-readiness rules, and roadmap.

### `protocols/`

Defines how agents should work. Protocols are behavioral rules and workflows, not one-off prompts.

### `templates/`

Reusable blank artifacts that can be copied into issues, prompts, PR descriptions, or project folders.

### `examples/`

Filled-in examples using fake data only. These should show how the templates are meant to be used.

### `.github/`

GitHub-native issue and pull request templates for structured collaboration.

## Naming Rules

- Protocols should end in `-protocol.md`.
- Templates should end in `.template.md`.
- Examples should start with `sample-` and use fake data only.
- Public-safety documents should clearly state what must not be committed.
