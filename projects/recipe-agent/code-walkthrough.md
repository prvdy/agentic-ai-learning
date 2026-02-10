# Code Walkthrough (Selective)

This document highlights key parts of the implementation rather than the full codebase.

## Agent Loop
The main loop controls when the agent evaluates state and chooses actions.

## Tool Invocation
Tools are called explicitly rather than embedded in prompts to keep behavior inspectable.

## Trade-offs
This design favors clarity over speed and is intended for learning purposes.
