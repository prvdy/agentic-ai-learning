# Agent Architecture

## Goal
Generate a usable recipe that satisfies user constraints.

## State
- user preferences
- ingredient availability
- dietary restrictions
- previous agent decisions

## Actions
- ask clarification
- generate recipe
- substitute ingredients
- revise recipe

## Loop
1. Evaluate current state
2. Decide next action
3. Execute action
4. Update state
5. Stop when constraints are satisfied
