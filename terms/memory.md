# Memory

## Definition

Memory is stored information that an agent system can use later, outside the
current immediate prompt.

## Why It Matters

Memory can make an agent more useful across time, but it also creates risks:
stale assumptions, privacy exposure, and hidden state that users cannot easily
inspect.

## Example

An assistant remembers a user's preferred timezone and project directory, then
uses that information when planning future reminders or file operations.

## Common Confusions

- Memory is not the same as the context window.
- Remembered information may be wrong, outdated, or too sensitive to use in a
  given setting.
- More memory is not always better; retrieval and authority rules matter.

## Related Terms

- [Context Window](context-window.md)
- [Retrieval](retrieval.md)
- [Trace](trace.md)
- [System Prompt](system-prompt.md)

## Sources

- Add sources as the project develops.
