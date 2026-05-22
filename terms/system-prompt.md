# System Prompt

## Definition

A system prompt is a high-priority instruction that shapes how a model or agent
should behave.

## Why It Matters

System prompts can define role, safety constraints, tool-use rules, formatting,
and boundaries. They are part of the control surface of an agent system.

## Example

A system prompt might tell a coding agent to avoid destructive commands, prefer
existing project patterns, and ask before sending external messages.

## Common Confusions

- A system prompt is not a guarantee of behavior.
- It should not be treated as the only safety layer.
- If prompts conflict with tools, permissions, or product design, the overall
  system can still fail.

## Related Terms

- [Guardrail](guardrail.md)
- [Agent](agent.md)
- [Context Window](context-window.md)
- [Trace](trace.md)

## Sources

- Add sources as the project develops.
