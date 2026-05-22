# Guardrail

## Definition

A guardrail is a constraint or check designed to prevent, detect, or limit
undesired behavior in an AI system.

## Why It Matters

Guardrails can reduce risk, but they are not magic. Good systems combine
guardrails with permissions, product design, logging, review, testing, and
recovery paths.

## Example

An agent may be allowed to draft a message but blocked from sending it until a
human approves the exact text.

## Common Confusions

- A prompt instruction can be a guardrail, but prompts alone are weak controls.
- A guardrail that silently blocks behavior can make systems confusing if the
  user cannot see what happened.
- Guardrails should be tested, not assumed.

## Related Terms

- [Autonomy](autonomy.md)
- [Human-in-the-Loop](human-in-the-loop.md)
- [Eval](eval.md)
- [Trace](trace.md)

## Sources

- Add sources as the project develops.
