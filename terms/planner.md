# Planner

## Definition

A planner is the part of an agent system that proposes or updates a sequence of
steps toward a goal.

## Why It Matters

Planning helps an agent organize multi-step work, but plans are only useful when
they stay connected to evidence, feedback, and changing constraints.

## Example

A coding agent creates a plan to inspect failing tests, identify the regression,
patch the code, rerun the relevant test, and summarize the fix.

## Common Confusions

- A plan is not proof that the agent understands the task.
- Planning can become busywork if the task is simple.
- A planner may be a prompt pattern, a separate model call, or ordinary control
  logic in the scaffold.

## Related Terms

- [Agent](agent.md)
- [Scaffold](scaffold.md)
- [Orchestrator](orchestrator.md)
- [Trace](trace.md)

## Sources

- Add sources as the project develops.
