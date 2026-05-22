# Retrieval

## Definition

Retrieval is the process of finding relevant information and adding it to an
AI system's current context.

## Why It Matters

Retrieval lets an agent use information that was not already in the prompt, such
as documents, code, messages, tickets, logs, or previous notes.

## Example

Before answering a question about a repository, an agent searches for the
relevant files and reads the sections most likely to contain the answer.

## Common Confusions

- Retrieval is not the same as memory, though memory may be retrieved.
- Similarity search is not authority. A retrieved note can be stale, wrong, or
  less authoritative than another source.
- Retrieval quality depends on indexing, ranking, chunking, and source hygiene.

## Related Terms

- [Memory](memory.md)
- [Context Window](context-window.md)
- [Trace](trace.md)
- [Agent](agent.md)

## Sources

- Add sources as the project develops.
