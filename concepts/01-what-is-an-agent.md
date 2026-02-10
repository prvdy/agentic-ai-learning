# What Is an Agent?

An agent is a system that:
- has a goal
- maintains some form of state
- can choose between actions
- evaluates when to continue or stop

Unlike a simple prompt-response system, an agent operates in a loop:
observe → decide → act → re-evaluate.

## Why This Matters
Agentic behavior emerges not from better prompts, but from:
- decision points
- feedback loops
- explicit control over actions

## Common Mistake
Calling any LLM workflow an “agent” even when it has no autonomy or decision-making.

## Key Insight
Most agent failures come from missing or poorly defined state, not model quality.
