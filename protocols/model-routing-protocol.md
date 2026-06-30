# Model Routing Protocol

## Purpose

Use this protocol to decide which AI tool should handle a software-engineering task.

The goal is not to crown one model as best. The goal is to route work to the tool that has the best fit for the task, context, privacy level, and expected output.

## Routing Questions

Before assigning work, ask:

1. Does the task require repo-aware editing?
2. Does the task require fresh research?
3. Does the task require code execution or tests?
4. Does the task involve private or sensitive data?
5. Does the task need long-form reasoning?
6. Does the task need a polished public artifact?
7. Does the task need a quick implementation spike?
8. Does the task need human review before action?

## Suggested Routing Table

| Task Type | Better Fit | Why |
|---|---|---|
| Multi-file repo edits | Claude Code or Codex | Works directly against project files. |
| Clear implementation task | Codex | Strong fit for scoped code changes. |
| Repo structure and documentation | Claude Code | Good for repeated file-aware iteration. |
| Strategy and synthesis | ChatGPT or Claude | Strong for planning and tradeoff analysis. |
| Fresh public research | ChatGPT with browsing or another research-enabled tool | Needs current sources. |
| Private command center work | Private repo-connected agent | Sensitive context should stay bounded. |
| Public examples and docs | Any agent with public-safety rules | Output must be sanitized and reviewable. |
| Quick prototype | Codex or Claude Code | Speed matters, but scope must stay tight. |

## Stop Conditions

Stop and ask for human review when:

- credentials are needed
- external systems would be changed
- production data is involved
- private information may be exposed
- the agent needs to choose between materially different designs
- the cost or risk of a mistake is high

## Output

A routed task should include:

- chosen tool
- reason for routing
- input context
- acceptance criteria
- stop conditions
- expected handoff artifact
