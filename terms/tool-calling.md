# Tool Calling

## Definition

Tool calling is when a model or agent requests that an external function,
service, or application be run on its behalf.

## Why It Matters

Tool calling lets an AI system do work the model cannot do by text generation
alone, such as searching files, reading a calendar, running tests, or sending a
message.

## Example

An agent asks a file-search tool to find every reference to `authToken`, then
uses the result to decide which files to inspect next.

## Common Confusions

- Tool calling is not the same as autonomy. A human can still approve every
  call.
- A tool call result is not guaranteed to be correct; it is another input that
  the system must interpret.

## Related Terms

- [Agent](agent.md)
- [MCP](mcp.md)
- [Orchestrator](orchestrator.md)
- [Trace](trace.md)

## Sources

- Add sources as the project develops.
