# Reviewability Protocol

## Purpose

Reviewability is the discipline of making AI-generated work easy to inspect, test, accept, reject, or revise.

The faster an agent works, the more important reviewability becomes.

## Rules

1. Keep changes small.
2. Prefer one objective per task.
3. Use clear acceptance criteria.
4. Avoid unrelated refactors.
5. Update documentation when behavior or structure changes.
6. Include tests when logic changes.
7. Explain assumptions.
8. Provide a clean handoff.

## Before Work Begins

A reviewable task should define:

- objective
- relevant files or folders
- in-scope work
- out-of-scope work
- constraints
- acceptance criteria
- stop conditions

## During Work

The agent should:

- avoid touching unrelated files
- preserve existing structure unless there is a reason to change it
- keep commits focused
- note any assumptions or unresolved questions
- avoid adding dependencies without justification

## Review Checklist

- [ ] The change maps to the requested objective.
- [ ] The diff is small enough to understand.
- [ ] The agent did not introduce unrelated cleanup.
- [ ] Sensitive or private data is not included.
- [ ] Tests or validation steps are documented.
- [ ] Documentation was updated if needed.
- [ ] Assumptions are visible.
- [ ] The next action is clear.

## Handoff Format

At the end, provide:

- Summary
- Changed files
- Validation performed
- Assumptions
- Risks
- Next steps
