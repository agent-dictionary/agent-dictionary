# Context Window

## Definition

The context window is the amount of text, code, tool output, images, or other
input a model can consider at one time.

## Why It Matters

An agent can only reason from what is in context plus what it can retrieve or
observe through tools. Important information outside the context window may as
well be invisible until it is brought back in.

## Example

If a coding agent reads a long log file, older parts of the conversation or
earlier file contents may no longer fit unless the system summarizes or
retrieves them again.

## Common Confusions

- A larger context window does not guarantee better understanding.
- Putting everything in context can add noise, cost, and stale assumptions.
- Context is temporary visibility, not durable memory.

## Related Terms

- [Memory](memory.md)
- [Retrieval](retrieval.md)
- [Trace](trace.md)
- [System Prompt](system-prompt.md)

## Sources

- Add sources as the project develops.
