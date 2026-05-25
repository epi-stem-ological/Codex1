# Operating Principles

## 1. Start With a Task Spec

Do not ask an agent to "build the thing" from vague intent. Start with a task spec that defines:

- objective
- background
- scope
- constraints
- files likely affected
- acceptance criteria
- stop conditions

## 2. Use Pure Focus

One session should have one main objective. Adjacent ideas go into a backlog, not into the current diff.

## 3. Keep Diffs Reviewable

Small, understandable changes are better than giant magical rewrites.

## 4. Require Acceptance Criteria

A task is not done because the agent says it is done. It is done when the acceptance criteria are satisfied.

## 5. Prefer Explicit Handoffs

When moving work between tools or sessions, create a handoff with:

- what changed
- what remains
- assumptions
- risks
- next action

## 6. Public-Safe by Default

All examples must use fake or sanitized data.

## 7. Templates Before Automation

Do not automate a workflow until the manual template works.

## 8. Agents Need Boundaries

A good agent instruction includes what not to do, not just what to do.
