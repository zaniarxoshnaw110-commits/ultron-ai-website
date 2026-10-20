---
name: superpowers-workflow
description: Apply a Superpowers-inspired plan, implementation, testing, and verification loop to repository changes.
---
# Superpowers-Inspired Workflow
This project-specific checklist is inspired by public engineering workflow practices in https://github.com/obra/superpowers. It is not an official copy or claim of affiliation.

## Before implementation
1. Read the relevant local skills and inspect the actual source files and deployment workflow.
2. State the problem and success criteria in one short paragraph.
3. Break multi-file work into ordered, independently reviewable changes.
4. Consider responsive, accessibility, failure, and reduced-motion cases before coding.

## During implementation
1. Prefer small, coherent changes over sweeping unreviewed rewrites.
2. For behavior changes, define the expected behavior first and check both success and empty/error paths.
3. Keep implementation and documentation aligned.
4. Avoid adding dependencies when platform-native code is enough.

## Before completion
1. Inspect the resulting diff and verify every changed path exists.
2. Run available syntax, link, and interaction checks; don't claim a check that wasn't run.
3. Verify commit and deployment status separately.
4. If a browser render was not inspected, say so.
5. Report concrete outcomes, limitations, and the next genuine blocker.

## Upstream references
- https://github.com/obra/superpowers/tree/main/skills/brainstorming
- https://github.com/obra/superpowers/tree/main/skills/writing-plans
- https://github.com/obra/superpowers/tree/main/skills/test-driven-development
- https://github.com/obra/superpowers/tree/main/skills/verification-before-completion