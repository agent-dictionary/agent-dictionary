# Orchestrator

## Definition

An orchestrator is the component that coordinates models, tools, agents, state,
and control flow in a larger AI system.

## Why It Matters

Orchestration determines which capability runs when. In complex systems, the
orchestrator can matter as much as the model because it controls routing,
permissions, retries, delegation, and handoffs.

## Example

An orchestrator sends a research task to a retrieval component, passes selected
sources to a summarizer, asks a verifier to check claims, and then returns a
final answer.

## Common Confusions

- An orchestrator is not necessarily intelligent; it may be deterministic code.
- Multi-agent orchestration is not automatically better than a simpler workflow.
- Orchestration should not hide who did what or why.

## Related Terms

- [Agent](agent.md)
- [Planner](planner.md)
- [Scaffold](scaffold.md)
- [Trace](trace.md)
- [MCP](mcp.md)

## Sources

- Add sources as the project develops.
