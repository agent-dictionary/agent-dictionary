# MCP

## Definition

MCP, or Model Context Protocol, is a protocol for connecting AI applications to
external tools and data sources through a shared interface.

## Why It Matters

MCP is meant to reduce one-off integrations. Instead of each app inventing its
own way to expose tools and resources to AI systems, MCP gives clients and
servers a common connection pattern.

## Example

An AI coding environment connects to an MCP server that exposes repository
issues, pull requests, or local simulator controls as callable tools.

## Common Confusions

- MCP is not itself an agent.
- MCP does not guarantee that a tool is safe to call.
- MCP is a connection protocol, not a substitute for product design,
  permissions, logging, or human approval.

## Related Terms

- [Tool Calling](tool-calling.md)
- [Orchestrator](orchestrator.md)
- [Guardrail](guardrail.md)
- [Trace](trace.md)

## Sources

- Model Context Protocol documentation: https://modelcontextprotocol.io/
