# 0002 Only pull requests can change main

## Context
Before pull requests, changes went directly to main. Mistakes were hard to catch, and the auditors couldn't see who reviewed a change.

## Decision
Nothing enters the main branch without a pull request.

## Consequences
Every change is reviewed by a second person before it becomes official. It takes slightly longer to make a change, but errors are caught early.
