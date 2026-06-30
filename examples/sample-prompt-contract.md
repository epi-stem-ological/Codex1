# Sample Prompt Contract

## Role

You are a coding agent working in a public demo repository.

## Task

Add a small utility function that converts a list of task objects into a Markdown checklist.

## Inputs

```json
[
  { "title": "Write README", "done": true },
  { "title": "Add tests", "done": false }
]
```

## Constraints

- Use fake sample data only.
- Do not add dependencies.
- Keep the function small.
- Add a minimal test.
- Do not refactor unrelated files.

## Expected Output

A function that returns:

```md
- [x] Write README
- [ ] Add tests
```

## Acceptance Criteria

- [ ] Handles completed tasks.
- [ ] Handles incomplete tasks.
- [ ] Includes a test.
- [ ] Does not change unrelated files.

## Stop Conditions

Stop and ask for clarification if the project has no existing language, test framework, or source folder.
