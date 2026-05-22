# Trace

## Definition

A trace is a record of what an AI system did during a run, including model
calls, tool calls, intermediate steps, inputs, outputs, or decisions.

## Why It Matters

Traces make agent behavior inspectable. They help developers debug failures,
understand costs, reproduce behavior, evaluate safety, and explain outcomes.

## Example

A trace for a coding task may show the user's request, files read, commands run,
patches applied, tests executed, and final response.

## Common Confusions

- A trace is not the same as an explanation, but it can provide evidence for
  one.
- Traces can contain sensitive data and need access controls.
- A missing trace makes agent behavior harder to audit.

## Related Terms

- [Tool Calling](tool-calling.md)
- [Eval](eval.md)
- [Guardrail](guardrail.md)
- [Orchestrator](orchestrator.md)

## Sources

- Add sources as the project develops.
