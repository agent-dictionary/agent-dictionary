# Scaffold

## Definition

A scaffold is the surrounding code, prompts, tools, memory, and control logic
that turn a model into a usable agent system.

## Why It Matters

Many agent capabilities come from the scaffold rather than the model alone. The
scaffold decides what the model can see, what it can call, how state is tracked,
and how errors are handled.

## Example

A coding-agent scaffold may include repository search, file editing, test
execution, planning, patch review, and final reporting.

## Common Confusions

- A better model does not remove the need for a good scaffold.
- A scaffold can make a system more capable, but also more dangerous if it
  exposes powerful tools without controls.

## Related Terms

- [Agent](agent.md)
- [Tool Calling](tool-calling.md)
- [Orchestrator](orchestrator.md)
- [Guardrail](guardrail.md)

## Sources

- Add sources as the project develops.
